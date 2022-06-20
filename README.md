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

<p>All these were necessary to <b>automate</b> the creation of objects on the 3D scene. Without these it would take a long time <b>mapping coordinates</b> for the objects and <b>textures</b> manually. These custom functions are <b>reusable</b> by including the <b>header files</b> in your project and calling the functions correctly with the required parameters.</p>

<b>Running the code</b>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/3d1.png"><br>
<b><i>Add three new lists</i></b><br>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/3d2.png"><br>
<b><i>Append moves made by each player to their respective lists</i></b><br>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/3d3.png"><br>
<b><i>Append the winning series of moves to the winning series list</i></b><br>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/3d4.png"><br>
<b><i>When making a move check if the move exists in a winning list containing the series of moves that lead to a win and select the next move from there</i></b><br>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/3d5.png"><br>
<b><i>Implement a depth first search to reduce the implementation time for the move selection process. Current implementation is breadth first search wich has high space and time complexity</i></b><br>
	<img src="https://github.com/Ritesh214/OpenGL_3D/blob/main/images/3d6.png"><br>


<p>Running file to can be found in the <b>Ritesh_FinalProject</b> folder, <b>OpenGLSample</b> folder <b><i>OpenGLSample.exe<i/></b>. Use right control for down movement and left control for up movement. Click and hold left mouse button for camera movement.</p>

<b>Skills</b>
<p>The skills illustrated here are in the use of glew and glad libraries in creating OpenGL 3D objects and scenes. I have also demonstrated how to use custom libraries to modularize the code and make the creation of objects on a scene easier.</p>
