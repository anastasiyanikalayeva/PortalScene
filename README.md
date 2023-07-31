# Three.js Portal Scene with Fireflies
This GitHub repository contains a captivating Three.js scene that showcases a portal with animated fireflies. The scene leverages the lil-gui library for interactive debugging and parameter adjustments. It features advanced lighting and shading effects to create a visually stunning experience. The repository includes the following main components:

## Dependencies
+ `lil-gui`: A lightweight GUI library used for debugging and parameter adjustment.
+ `three`: The core Three.js library that provides the foundation for 3D rendering and animations.
+ `three/examples/jsm/controls/OrbitControls.js`: A module for camera controls that enable users to orbit around the scene.
+ `three/examples/jsm/loaders/GLTFLoader.js`: A module for loading GLTF models into the scene.
+ `three/examples/jsm/loaders/DRACOLoader.js`: A module for loading compressed DRACO models.
+ `./shaders/fireflies/vertex.glsl` and `./shaders/fireflies/fragment.glsl`: GLSL shaders used to create the mesmerizing fireflies effect.
+ `./shaders/portal/vertex.glsl` and `./shaders/portal/fragment.glsl`: GLSL shaders used to render the portal light effect.

## Description
The repository provides a detailed implementation of the scene, including the following key elements:
1. Scene Setup: The JavaScript code sets up the Three.js scene, initializes the renderer, and creates a debug GUI to control various parameters.
2. Model Loading: It loads a 3D model named 'portal.glb' using the GLTFLoader and applies different materials to specific parts of the model.
3. Materials and Textures: Various materials are used, including a baked material, pole light material, and a portal light material. Textures like 'baked.jpg' are also loaded to create realistic surfaces. 
4. Fireflies: A captivating fireflies effect is achieved by creating a custom shader material and attaching it to a points cloud geometry.
5. Camera and Controls: The scene is viewed through a perspective camera with OrbitControls for easy user navigation.
6. Animation: The scene incorporates time-based animation for the portal light and fireflies, adding a dynamic and engaging experience.
7. Responsive Design: The scene adapts to different window sizes and device pixel ratios to ensure a seamless experience across various devices.

## Usage
To use the Portal Scene, simply open the [link](https://anastasiyanikalayeva.github.io/PortalScene/) in your web browser and adjust the controls located in the top right corner of the screen. The Portal Scene is optimized for use in modern web browsers, including Google Chrome, Mozilla Firefox, and Microsoft Edge.