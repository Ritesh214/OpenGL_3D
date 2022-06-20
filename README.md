<h2>OpenGL 3D Objects and Scene</h2>
<p>Using OpenGL <b>glad</b> and <b>GLFW</b> libraries to draw 3D objects and scenes</p>
<b>The Scene</b>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/scene.png"><br>
<p>This project was chosen because of the many <b>complex objects</b> in it that require multiple objects to create. This presents a reasonable challenge that will ensure an in-depth study of how to create <b>various objects</b> and also meet the minimum requirements of having at least four of the mentioned objects to include. These are the <b>cube, cylinder, plane, pyramid, sphere</b> and <b>torus</b>.<br>
I was able to program the scene by first learning how to create objects in the <b>primitive</b> way using four different ways to generate a cube. Once I understood the concept, I took it a step further by using classes to create objects like <b>cylinders</b> and <b>spheres</b>. Using classes made it easier to define objects in the scene since I only needed to pass the defining parameters and the class would take care of the rest.</p>

<b>The controls</b>
<p>For navigation in my scenes, I utilized the following keys:</p>
<p><i>
• W- forward
• S- backward
• A- left
• D- right
• Left Ctrl- up
• Right Ctrl- down
</i></p>
<p>For the movement of the <b>light cube</b>, I used the following keys:</p>
<p><i>
• Y- forward
• H- backward
• G- left
• J- right
• M- up
• N- down
</i></p>
<p>I also used the mouse movement to move around the object using the <b>mouse_callback</b> function where the <b>x and y positions</b> of the mouse were mapped onto the <b>lookAt</b> function values.</p>

<b>Custom functions</b>
<p>My custom functions included the following:</p>
<p><i>
• Camera
• Cylinder
• Sphere
• Controls
• Objloader
• Shader
• staticMesh3D
• Texture
</i></p>

<p>All these were necessary to automate the creation of objects on the 3D scene. Without these it would take a long time mapping coordinates for the objects and textures manually. These custom functions are reusable by including the header files in your project and calling the functions correctly with the required parameters.</p>
