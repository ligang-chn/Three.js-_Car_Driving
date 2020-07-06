Three.js_Car_Driving
========
Hi there, this is my first attempt to create an interactive 3D world using Three.js.


#### 1 What is Three.js ?
 Three.js  —— JavaScript 3D library

The aim of three.js project is to create an easy to use, lightweight, 3D library with a default WebGL renderer. The library also provides Canvas 2D, SVG and CSS3D renderers in the examples.

[Examples](http://threejs.org/examples/) &mdash;
[Documentation](http://threejs.org/docs/) &mdash;
[Wiki](https://github.com/mrdoob/three.js/wiki) &mdash;
[Migrating](https://github.com/mrdoob/three.js/wiki/Migration-Guide) &mdash;
[Questions](http://stackoverflow.com/questions/tagged/three.js) &mdash;
[Forum](https://discourse.threejs.org/) &mdash;
[Slack](https://join.slack.com/t/threejs/shared_invite/enQtMzYxMzczODM2OTgxLTQ1YmY4YTQxOTFjNDAzYmQ4NjU2YzRhNzliY2RiNDEyYjU2MjhhODgyYWQ5Y2MyZTU3MWNkOGVmOGRhOTQzYTk) &mdash;
[Discord](https://discordapp.com/invite/HF4UdyF)

#### 2 ScreenShots




#### 3 Intruduction
Based on the official case of Three.js webgl_materials_car rewritten, the features are as follows:

1\) Through XMLHttpRequest, you can request a specific URL without refreshing the page to obtain the scene configuration file;

2\) Use dat.Gui to add controls such as buttons and tabs;

3\) You can drive the car using the WASD keys.


#### 3 Structure


Three.js_Car_Driving-master
- build——The result of packaging each code module in the src directory.
	- three.js——The threejs engine library to be introduced in the .html file during development is the same as the introduction of jquery, which can assist browser debugging.
    - three.min.js——The compressed structure file of three.js is smaller and can be introduced in .html when you can deploy the project.
  
- examples——There are a lot of threejs cases in it. Usually, you can find a certain API, method or attribute through code editing to locate a case.
  
- src——The various modules of the Three.js engine can be deeply understood by reading the source code of the threejs engine.
    - index.html——Open this file to view threejs API documents offline.
    
- utils——Some auxiliary tools
    - \utils\exporters\blender——Blender plugin for exporting threejs files.

>Note:
>json——scenarios config


#### 4 Usage

1\) Clone or download the whole project.
>git clone https://github.com/ligang-chn/Three.js-_Car_Driving.git

2\) Open it as a project by VS Code.

3\) In the EXTENSIONS of VS Code,install the `Live Server` extension.
>Live Server——Launch a development local Server with live reload feature for static & dynamic pages.

4\) Now ,  you can find the option(`Open with Live Server`) in the right-click menu.

5\) Yee~! It will run on the browser.

#### 5 Browser Support
I've tested this project in Google Chrome (83.0.4103.116) rendering [35 ~ 121] fps.

#### 6 Debug

- F12: Bring up the debug console.

- console.log("print string",variable);——Print the result or variable;


#### 7 Oh~ No~

Dear programer:

when I wrote this code, only god and I know how it worked.

Now, only god knows it!

Therefore, if you are trying to optimize this routine and it fails (most surely), please increase this counter as a waring for the next person:

total_hours_wasted_here = 42
