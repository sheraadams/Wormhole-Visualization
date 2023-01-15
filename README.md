# Documentation

This program is a visualization/ simulation program designed to allow an interactive 3D environment. 

![44](https://user-images.githubusercontent.com/110789514/211556500-e5f18c06-389c-4f67-a1b5-4b9c389a6414.png)

## Note

Cylinder.cpp and Cylinder.h class and algorithms are not included but can be found at:  https://songho.ca/opengl/gl_cylinder.html#cylinder

## Instructions 
Runs in Microsoft Visual studio.

Set linker dependencies: assimp.lib, opengl32.lib, glew32.lib, glfw3.lib along with usual dependencies.

1. add libraries: glfw3.lib, opengl32.lib, assimp.lib, glew32.lib

2. add existing items in MS Visual Studio

3. if filestystem.h warnings: use #pragma warning(disable: 4996)

4. Go to C++ language properties and add most recent c++ version as this may not be selected not default. 

5.add #define STB_IMAGE_IMPLEMENTATION above stb_image.h to one cpp file, also stb macro defines (see https://github.com/nothings/stb/blob/master/stb_image.h)

## License
Image by wikiImages via Pixabay
Image by XtravaganT via Adobe Stock.

## License

Credit to LearnOpenGL for shaders, camera and glfw functions. 

https://github.com/JoeyDeVries/LearnOpenGL/blob/master/LICENSE.md

Learn OpenGL, extensive tutorial resource for learning Modern OpenGL. (n.d.-c). https://learnopengl.com/
