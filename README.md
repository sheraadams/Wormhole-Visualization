# Documentation

This program is a visualization/ simulation program designed to allow an interactive 3D environment. 

![5](https://user-images.githubusercontent.com/110789514/211426193-6ec594f8-c643-4356-a853-41042a6f4715.png)

## Attribution

Joey Devries and LearnOpenGL as much of this repository is inspired by this site. 

sphere algorithm - LearnOpenGL 

Cylinder algorithm - Songho Ahn

## Instructions 
Runs in Microsoft Visual studio.

Set VC++ include and libs directory to usual settings.

Set additional libraries to usual settings and dependencies.

Set linker dependencies: assimp.lib, opengl32.lib, glew32.lib, glfw3.lib along with usual dependencies.

1. Clone. Settings are x64 

2. Modify solution properties, all solutions debug > VCC++
add includes, add libraries

3. go to linker link additional libraries of config, dlls, bin, resources
go to linker > input in properties add 
glfw3.lib, opengl32.lib, assimp.lib, glew32.lib
4. go to project add existing items if missing items from below:
glad.c, .pdbs, .vs, .fs, all files not including Visual Studio specific files

5. if filestystem.h warnings: 
after class FileSystem {
enter:
..."
public:
#pragma warning(disable: 4996)
..."

6. Go to C++ language properties and add most recent c++ version as this may not be selected not default. 

7. if using stb_image type above stb include: 
#define STB_IMAGE_IMPLEMENTATION above stb_image.h
if this does not resolve add more these defines:
#define STB_IMAGE_IMPLEMENTATION
#define STBI_ASSERT(x)
#define STBI_MALLOC
#define STBI_REALLOC 
#define STBI_FREE
#define STBI_NO_FAILURE_STRINGS
see https://github.com/nothings/stb/blob/master/stb_image.h

## License

Credit to LearnOpenGL for shaders, camera and glfw functions. 

https://github.com/JoeyDeVries/LearnOpenGL/blob/master/LICENSE.md

## References

Learn OpenGL, extensive tutorial resource for learning Modern OpenGL. (n.d.-c). https://learnopengl.com/
