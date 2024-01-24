# WebGL_Tetrahedron_Project
 This Project allows users to interactively adjust the position, rotation, and scale of a tetrahedron using sliders and input fields, thus providing an example of basic 3D graphics manipulation in the browser environment.

## Overview
This HTML and JavaScript code creates a simple WebGL application to render a tetrahedron and allow users to interactively adjust its position, rotation angles, and scale.

- HTML Section:
  
Canvas Element:

<canvas id="gl-canvas" width="512" height="512">: Defines the canvas element for rendering WebGL graphics.

Shader Scripts:

Vertex and fragment shader scripts, with IDs "vertex-shader" and "fragment-shader" respectively.

JavaScript Imports:

Importing the required JavaScript files (webgl-utils.js, initShaders.js and MV.js).

JavaScript File:

<script type="text/javascript" src="hw3.js"></script>: Link to the JavaScript file containing the WebGL application code.

- JavaScript Section (hw3.js):
  
Global Variables:

Various variables to store transformation parameters, camera parameters, matrices, and arrays for points and colors.

tetrahedron() Function:

Creates the points and colors for a tetrahedron, populating the points and colors arrays.

window.onload Function:

Initializes the WebGL context, sets up shaders, and creates attribute buffers.

Event Listeners:

FOVY defines callback functions for sliders and input fields to update parameters such as camera position, target position, object translation, scaling and rotation.

Reset Button Callback:

Resets all transformation parameters to their initial values.

rendering Function:

It renders the scene by calculating model-view and projection matrices based on user input. It uses requestAnimationFrame for continuous rendering.
