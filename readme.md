**3D Website with Three.js, Spline & Midjourney** \n
This project demonstrates the creation of a 3D website using Three.js, Spline, and Midjourney. The website incorporates a Choose Your Own Adventure concept and explores different approaches to building it.

**Overview**
The project consists of two parts: creating the website using the Spline editor tool without writing any code and recreating it using Three.js with code. The Spline editor tool allows for web-based 3D editing, while Three.js is a JavaScript library for creating 3D graphics on the web.

**Part 1: Creating the Website with Spline (No Code)**
Access the Spline editor tool at spline.design.
Import an image and place it in the scene.
Add a sphere and position it accordingly.
Switch the material from color to gradient and choose colors from the image using the eyedropper tool.
Adjust the gradient angle to match the image.
Duplicate the sphere and repeat the process for all the other spheres.
Use the pen tool to draw a path for the complex background shape, adjusting the bezier handles to create curves.
Convert the path to a shape and set its extrusion settings.
Customize the extrusion shape as a star, adjusting the sides, start and end scale values, and size.
Switch the material from color to noise, selecting colors using the color picker.
Adjust the scale and colors to match the visuals.
Fine-tune the lighting and shininess of the materials.
Arrange the lights within the scene.
Export the project as HTML using the Spline editor tool.

**Part 2: Recreating the Website with Three.js (Code Implementation)**
Change the version of Three.js to use a library called Mod 3, enabling geometry manipulation.
Include the necessary libraries, including Mod 3, Three.js plugin, a Perlin noise library, and a custom Mod 3 plugin using Perlin noise.
Set up a basic Three.js scene.
Create an animation loop using the render function.
Add a basic test cube to the scene.
Adjust the CSS height of the canvas element for proper display.
Create a custom shape resembling a star with 100 points.
Extrude the shape using the specified settings and extrusion path.
Apply materials and textures to the shape, ensuring repeat wrapping for animation effects.
Set up a delta variable to adjust the offset of the texture over time.
Utilize Mod 3 to distort the shape, adding modifiers like taper and twist.
Apply the modifier stack to the shape within the animation loop.
Add fog to the scene to create a tapering effect.
Match the fog color with the background color for seamless blending.
Add circles and lights to the scene, allowing for dynamic manipulation using DAT GUI.
Implement a button to add spheres dynamically.
Adjust the parameters of the circles and lights using DAT GUI.
Update the scene to reflect the changes in the circles and lights.
Enable shadows for the scene to enhance the visual effect.
Build the CSS and markup for the UI elements.
