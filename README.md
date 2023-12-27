# UnityLightingOpt
A unity lighting optimization project in VR environment

Unity Version: 2021.3.18.f1c1

The project requires a VR headset to handle everthing, and there are two methods implemented in the project, which is LOD for real-time lights exclusively and light baking for static lights. 
When the scene is running, you can use the buttons to control if each module should be enabled/disabled.
The effect of optimization can be checked from the FPS param, which is also visulized on the screen.

* Create a new project(Using VR template) with corresponding unity version, then delete all assets and import all from the unitypackage. The primary scene can be found at "Scene/SampleScene". Moreover, you may have to rebake the static lights at Windows->Rendering->Lighting->Scene->Generate Lights
