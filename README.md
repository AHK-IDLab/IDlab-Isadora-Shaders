# IDlab-Isadora-Shaders
A collection of GLSL actors for Isadora made by [Frederick Rodrigues](http://www.fredrodrigues.net/) in residency at IDlab at the AHK Amsterdam


# IDlab
IDlab is the Interdisciplinary Digital Laboratory situated at the Academy of Theatre and Dance AHK Amsterdam.

https://www.atd.ahk.nl/en/idlab/

The IDlab has supported the creation of these effects through its Artist In Residency program in March 2020.

The code in these effects was adapted from 2 main sources:
https://github.com/maxillacult/ofxPostGlitch
and
https://github.com/neilmendoza/ofxPostProcessing


# Installation

These files are made to work with Isadora (https://troikatronix.com/) a node based real time media framework for live performance. To use these effects you will need to have Isadora installed.

* Download or clone this repository.

* Open Isadora and go to Help ->  Open Plugin Folder -> Troika Tronix GLSL Shaders

* Copy the contents of the shader folder into the Troika Tronix GLSL Shaders folder

* Restart Isadora

Now you can open the example patches.

There are 2 example files:

The "IDLAB Shader Examples still image.izz" patch uses a still image to show how the effects work.
 

The "IDLAB Shader Examples Live video.izz" uses a live video input, you will need to configure your camera in the capture settings and then hit start capture.

If your webcam or video input is configured correctly the effects will process the live video input.

Please post videos or pictures of what you do with this to the Isadora forum thread:
https://community.troikatronix.com/topic/6474/some-new-glsl-effects

Have fun!
