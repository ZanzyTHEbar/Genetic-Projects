<script src="https://aframe.io/releases/0.6.0/aframe.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/aframevr    /aframe@1c2407b26c61958baa93967b5412487cd94b290b/dist/aframe-master.min.js"></script>
<script src='https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar-nft.js'>   </script>
<!-- include ar.js for A-Frame -->
<body style='margin : 0px; overflow: hidden;'>
  <a-scene embedded arjs>
    <!-- create your content here. just a box for now -->
    <a-box position='0 0.5 0' material='opacity: 0.5;'></a-box>
    <!-- define a camera which will move according to the marker position -->
    <a-marker-camera preset='custom' type='pattern' url='assets/ppattern-download.patt'></a-marker-camera>
    <script>
    window.onload = function() {
    AFRAME.registerComponent('videohandler', {
        init: function () {
            var marker = this.el;

            this.vid = document.querySelector("#vid");

            marker.addEventListener('markerFound', function () {
                this.vid.play();
            }.bind(this));

    marker.addEventListener('markerLost', function() {
        this.vid.pause();
        this.vid.currentTime = 0;
    }.bind(this));
        }
    });
};
</script>

<style>
.arjs-loader {
    height: 100%;
    width: 100%;
    position: absolute;
    top: 0;
    left: 0;
    background-color: rgba(0, 0, 0, 0.8);
    z-index: 9999;
    display: flex;
    justify-content: center;
    align-items: center;
}

.arjs-loader div {
    text-align: center;
    font-size: 1.25em;
    color: white;
}
</style>

<body style='margin : 0px; overflow: hidden;'>
<div class="arjs-loader">
    <div>Loading, please wait...</div>
</div>
<a-scene
    vr-mode-ui="enabled: false;"
    renderer='antialias: true; alpha: true; precision: mediump;'
    embedded arjs='trackingMethod: best; sourceType: webcam; debugUIEnabled: false;'>

    <a-assets>
        <video src="assets/urobologio.mp4"
            preload="auto" id="vid" response-type="arraybuffer" loop
            autoplay autofocus playsinline>
        </video>
    </a-assets>

    <a-nft
        videohandler
        type='nft' url='nft/urobologio/urobologio-image/urobologio'

    >
        <a-video src="#vid" position="10 -10 -175" rotation="-90 0 0" width='140'     height='140'>
        </a-video>
    </a-nft>
    <a-entity camera></a-entity>

  </a-scene>
</body>
