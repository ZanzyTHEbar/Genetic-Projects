<!-- <div align="center">
 <br>
 <a href="https://github.com/ZanzyTHEbar/Genetic-Projects/blob/master/dna.svg">
  <img src="dna.svg" width="800" height="400" alt="Welcome my Genetic Engineering Projects">
 </a>
 <br>
</div>
<br> -->

<body>
    <div align="center">
    <br>
    <svg
    fill="none"
    version="1.1"
    xmlns="http://www.w3.org/2000/svg"
    viewBox="0 0 1225.5 792.5">
    <foreignObject width="100% height="100%">
            <div xmlns="http://www.w3.org/1999/xhtml">
                <style>
                    $color1: #55c1ff;
                    $color2: #dc6bad;
                    $background: #0c0c0c;
                    $white: #ffffff;

                    .body{
                    display: flex;
                    flex-direction: column;
                    align-items: center;
                    justify-content: center;
                    margin: 0;
                    width: 100%;
                    height: 400px;
                    background-size: 600% 400%;
                    border-radius: 10px;
                    color: white;
                    text-align: center;
                    background-color: $background;
                    }

                    .container{
                    position: fixed;
                    top: 0;
                    bottom: 0;
                    left: 0;
                    right: 0;
                    margin: auto;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    }

                    .dnaloader{
                    height: 10rem;
                    width: 30rem;
                    top: 0;
                    bottom: 0;
                    left: 0;
                    right: 0;
                    margin: auto;
                    display: flex;
                    justify-content: space-evenly;
                    align-items: center;
                    animation: rotateDna 15s linear infinite;
                    }

                    .spike{
                    height: 80%;
                    width: 0;
                    position: relative;
                    }

                    .spike::before{
                    content: "";
                    position: absolute;
                    height: 1rem;
                    width: 1rem;
                    left: 0;
                    right: 0;
                    transform: translateX(-50%);
                    border-radius: 500px;
                    margin: auto;
                    }

                    .spike::after{
                    content: "";
                    position: absolute;
                    height: 1rem;
                    width: 1rem;
                    left: 0;
                    right: 0;
                    transform: translateX(-50%);
                    border-radius: 500px;
                    margin: auto;
                    }

                    .dnaloader::before{
                    top: 0;
                    background-color: $color1;
                    animation: beforeAnimate 1.5s linear infinite;
                    }

                    .dnaloader::after{
                    bottom: 0;
                    background-color: $color2;
                    animation: afterAnimate 1.5s linear infinite;
                    }


                    @for $i from 1 through 15 {
                    .spike:nth-child(#{$i}){
                        .spike::before, .spike::after{
                        animation-delay: #{$i*0.15}s;
                        }
                    }
                    }

                    @keyframes beforeAnimate{
                    0%{
                        top: 0;
                        transform: translateX(-50%) translateY(0) scale(0.5);
                        opacity: 0.25;
                    }
                    25%{
                        transform: translateX(-50%) translateY(0) scale(0.5);
                        opacity: 0.5;
                        z-index: -1;
                    }
                    50%{
                        top: 100%;
                        transform: translateX(-50%) translateY(-100%) scale(0.5);
                        opacity: 0.75;
                    }
                    75%{
                        transform: translateX(-50%) translateY(0) scale(0.5);
                        opacity: 0.5;
                        z-index: 1;
                    }
                    100%{
                        top: 0;
                        transform: translateX(-50%) translateY(0) scale(0.5);
                        opacity: 0.75;
                    }
                    }

                    @keyframes afterAnimate{
                    0%{
                        bottom: 0;
                        transform: translateX(-50%) translateY(0) scale(0.5);
                        opacity: 0.25;
                    }
                    25%{
                        transform: translateX(-50%) translateY(-100%) scale(0.5);
                        opacity: 1;
                        z-index: 1;
                    }
                    50%{
                        bottom: 100%;
                        transform: translateX(-50%) translateY(100%) scale(0.5);
                        opacity: 0.75;
                    }
                    75%{
                        transform: translateX(-50%) translateY(-100%) scale(0.5);
                        opacity: 0.50;
                        z-index: -1;
                    }
                    100%{
                        bottom: 0;
                        transform: translateX(-50%) translateY(0) scale(0.5);
                        opacity: 0.75;
                    }
                    }

                    @keyframes rotateDna{
                    0%{
                        transform: rotate(0deg);
                    }
                    100%{
                        transform: rotate(360deg);
                    }
                    }
                </style>
                <div class="body">
                    <div class="container">
                        <div class="dnaloader">
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                            <div class="spike"></div>
                        </div>
                    </div>
                </div>
            </div>
    </foreignObject>
    </svg>
    </div>
    <br>
</body>

# :man_technologist: [ZanzyTHEbar](https://ZanzyTHEbar.github.io)

## 🧬 Our Projects

<!-- START OF PROFILE STACK, DO NOT REMOVE -->

| 🧬  **Technology**                                                                                                                                                                             | :rocket: **Projects**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [![Visual Studio Code](https://img.shields.io/static/v1?label=&message=Genetic%20Engineering&color=975db2&logo=visual-studio-code&logoColor=FFFFFF)](https://en.wikipedia.org/wiki/Molecular_biology) | [![PSilocybin](https://img.shields.io/static/v1?label=Ecoli-Psilocybin&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/Genetic-Projects/tree/master/Psilocybin)                                                                                                                                                                                                                                                                                                                                         |
| [![Visual Studio Code](https://img.shields.io/static/v1?label=&message=Genetic%20Engineering&color=808&logo=visual-studio-code&logoColor=FFFFFF)](https://en.wikipedia.org/wiki/Molecular_biology) | [![Custom Plants](https://img.shields.io/static/v1?label=Custom%20Plants&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/Genetic-Projects/tree/master/Custom%20Plants)                                                                                                                                                                                                                                                           |
 | [![Visual Studio Code](https://img.shields.io/static/v1?label=&message=Genetic%20Engineering&color=F71&logo=visual-studio-code&logoColor=FFFFFF)](https://en.wikipedia.org/wiki/Molecular_biology)                                                                   | [![Lactose](https://img.shields.io/static/v1?label=Lactose&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/Genetic-Projects/tree/master/Lactose)
<!--| [![Python](https://img.shields.io/static/v1?label=&message=Python&color=3C78A9&logo=python&logoColor=FFFFFF)](https://www.python.org/)                                                                   | [![UFO-Detector](https://img.shields.io/static/v1?label=UFO-Detector&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/UFO-Detector)[![MicroPythonAsyncWebserver](https://img.shields.io/static/v1?label=MicroPythonAsyncWebserver&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/MicroPythonAsyncWebserver)                                                                                                                                                                 |
 | [![Swift](https://img.shields.io/static/v1?label=&message=Swift&color=FA7343&logo=swift&logoColor=FFFFFF)](https://developer.apple.com/swift/)                                                           | [![StopCallingMe.ca](https://img.shields.io/static/v1?label=Stop-Calling-Me&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/Stop-Calling-Me) [![MacSwitch](<https://img.shields.io/static/v1?label=MacSwitch%20(WIP)&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605>)](https://github.com/ZanzyTHEbar/MacSwitch)                                                                                                                                                   |
| [![HTML](https://img.shields.io/static/v1?label=&message=HTML&color=e6472f&logo=HTML5&logoColor=FFFFFF)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)                                  | [![ZanzyTHEbar.github.io](https://img.shields.io/static/v1?label=My%20Website&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/ZanzyTHEbar.github.io) [![CoolMoodleDescription](https://img.shields.io/static/v1?label=CoolMoodleDescription&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/CoolMoodleDescription)                                                                                                                       |
| [![C#](https://img.shields.io/static/v1?label=&message=C%23&color=178600&logo=visual-studio-code&logoColor=FFFFFF)](https://en.wikipedia.org/wiki/Visual_Basic_.NET)                                     | [![Among-Us-Trasher](https://img.shields.io/static/v1?label=Among-Us-Trasher&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/Among-Us-Trasher) [![skyline-patcher](https://img.shields.io/static/v1?label=skyline-patcher&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/skyline-patcher)                                                                                                                                         |
| [![Bash](https://img.shields.io/static/v1?label=&message=Bash&color=83e066&logo=GNU-Bash&logoColor=FFFFFF)](https://www.gnu.org/software/bash/)                                                          | [![fakesigner](https://img.shields.io/static/v1?label=fakesigner&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/fakesigner) [![iInfo](https://img.shields.io/static/v1?label=iInfo&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/iInfo) [![app-packager](https://img.shields.io/static/v1?label=app-packager&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/app-packager) |
| [![Processing](https://img.shields.io/static/v1?label=&message=Processing&color=0097d8&logo=java&logoColor=FFFFFF)](https://processing.org/)                                                             | [![PixelSorter](https://img.shields.io/static/v1?label=PixelSorter&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/PixelSorter) [![NovationLaunchKeyLights](https://img.shields.io/static/v1?label=NovationLaunchKeyLights&message=%20&color=000605&logo=github&logoColor=white&labelColor=000605)](https://github.com/ZanzyTHEbar/NovationLaunchKeyLights)                                                                                                                           |
 -->

<!-- END OF PROFILE STACK, DO NOT REMOVE - Credit to user @basti564 for the design inspirations -->

</div>
<h2>Would you like to contact us?</h2>
<p>Hey! <b><i>Think we share any common interests?</i></b> Let's hop on discord (below) and talk about things!</p>
<p><a href="https://discord.gg/Bz52xHvZ3c"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"></a>
</p>
<br>

:star: ZanzyTHEbar / DaOfficialWizard#2377 (Discord) <p><img src="https://github.com/ZanzyTHEbar/Genetic-Projects/blob/master/imgs/wizard.svg" width="150" height="80" alt="Wizard Emoji"></p>

<br>

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/hbatproject)

![Profile Views](https://komarev.com/ghpvc/?username=ZanzyTHEbar&color=grey)