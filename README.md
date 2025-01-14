## Documentation

This program is a visualization/ simulation program designed to allow an interactive 3D environment for educational purposes. Created in C++ using GLFW and OpenGL. 

https://www.youtube.com/watch?v=PsuJ5Sfq4w0

![copies_AdobeExpress](https://user-images.githubusercontent.com/110789514/226143875-273133d1-174e-41a4-9976-d057415bfc1f.gif)

![44](https://user-images.githubusercontent.com/110789514/211556500-e5f18c06-389c-4f67-a1b5-4b9c389a6414.png)

## References

Ahn, Song Ho (n.d.) Cylinder. http://www.songho.ca/opengl/gl_cylinder.html

JoeyDeVries, J. (n.d.). LearnOpenGL/LICENSE.md at master · JoeyDeVries/LearnOpenGL. GitHub. https://github.com/JoeyDeVries/LearnOpenGL/blob/master/LICENSE.md

Learn OpenGL, extensive tutorial resource for learning Modern OpenGL. (n.d.-d). https://learnopengl.com/

XtravaganT. (n.d.). Space nebula and galaxy. https://as1.ftcdn.net/v2/jpg/05/29/87/36/1000_F_529873693_V74iNOFH3z0LxitPFigGfuaU3lDxVl5P.jpg

WikiImages. (n.d.). Orion Nebula. https://pixabay.com/photos/orion-nebula-emission-nebula-11107/

## XCode Usage

Open a terminal in the project directory and run the code to remove the old build folder and generate a new one with the Xcode project file.
```bash
mkdir build
cd build
cmake -G Xcode ..

# Usage: when updating the build folder
rm -rf build
```
Set the working directory in Xcode using Product > Scheme > Edit Scheme > Run Debug > Options > Working Directory > (Check Set Custom) > Project directory/build.

Build and run the project.

## License:

The code is based on various tutorial code from LearnOpenGL.com.

Tutorial code is © Joey DeVries and licensed under the CC BY 4.0 License.

Modifications and additional contributions are © Shera Adams and licensed under the Apache 2.0 License.

Proudly crafted with ❤️ by Shera Adams.
