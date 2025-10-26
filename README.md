3D Scene Project
Overview

I created a workspace setup where each object is built from simple 3D shapes—like the microphone using a cylinder and a sphere, the laptop made of boxes, and the mouse as a smooth, tapered shape. I applied textures to the laptop and table to make them feel more realistic and set up two light sources, including a colored point light near the microphone, to give the scene depth. Users can navigate around the scene using WASD and QE keys for movement, the mouse for pitch and yaw, and even adjust camera speed with the scroll wheel. The main logic of the project is handled in maincode.cpp, which initializes the scene, manages the game loop, and coordinates input and rendering.

Architecture & Files

The project uses SceneManager.cpp to organize the preparation and rendering of 3D objects, including textures, materials, and lighting. Shader programs are handled separately in the shaders directory, allowing for custom lighting and surface effects, which gives the objects in the scene a more realistic and dynamic look. By separating responsibilities into maincode.cpp, SceneManager.cpp, and the shader files, I could iterate on different parts of the program without affecting the overall structure.

Learning & Skills

This was my first time working with OpenGL and Object3D, so it was definitely one of the most challenging projects I’ve tackled. I learned how all the different pieces—modeling, textures, lighting, camera controls, and shaders—need to work together to make the scene feel alive. I also realized that small tweaks to light placement, shader parameters, or camera angles can completely change how a scene looks, which taught me to be patient and methodical when iterating.

Reflections & Future Goals

I still have questions about computational graphics, such as optimizing rendering for more complex scenes and creating realistic physics interactions between objects. I’d also like to explore advanced shaders, real-time lighting, and more dynamic scene interactions in future projects. These skills will be very useful as I continue in programming and software development. Learning how to build interactive 3D environments gives me a foundation for game development, simulations, or visualization tools. Overall, I feel more confident tackling projects that require combining multiple technical components into one cohesive program.
