<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Hello!</title>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script type="text/javascript" src="https://aframe.io/releases/0.8.2/aframe.min.js"></script>
    <script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.7.1/aframe/build/aframe-ar.js"></script>
    <script type="text/javascript" src="https://rawgit.com/donmccurdy/aframe-extras/master/dist/aframe-extras.loaders.min.js"></script>

    <!-- import the webpage's javascript file -->
    <script>
    AFRAME.registerComponent("vidhandler", {
    // ...
    init: function () {
      // Set up initial state and variables.
      this.toggle = false;
      this.vid = document.querySelector("#vid");
      this.vid.pause();
    },
    tick: function () {
      if (this.el.object3D.visible == true) {
        if (!this.toggle) {
          this.toggle = true;
          this.vid.play();
        }
      } else {
        this.toggle = false;
        this.vid.pause();
      }
    }
  });</script>


    <a-scene vr-mode-ui="enabled: false" artoolkit='sourceType: webcam; detectionMode: mono; maxDetectionRate: 90;' arjs='debugUIEnabled: false;detectionMode: mono_and_matrix; matrixCodeType: 3x3;'>

    <a-assets>
        <video muted id="vid" response-type="arraybuffer" loop="false" crossorigin webkit-playsinline playsinline controls>
            <source src="assets/videoplayback.mp4" type="video/mp4">
        </video>
    </a-assets>

     <!-- define a camera which will move according to the marker position -->
    <a-marker-camera preset='custom' type='pattern' url='assets/pattern-download.patt'></a-marker-camera>
        <a-entity position="0 0 0">
            <a-video width="4" height="3" rotation="-90 0 0" material='transparent:true;shader:flat;side:double;src:#vid'></a-video>
        </a-entity>
    </a-marker>

    <a-entity camera>
        <a-entity cursor="rayOrigin: mouse;fuse: false;"></a-entity>
    </a-entity>

</a-scene>

  </body>
</html>
