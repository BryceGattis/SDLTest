# SDLTest
My first CMake project with a very basic SDL initialization.

Biggest challenge was learning some basic CMake syntax and determining if I should vendor SDL or not into the repo.

## Dependencies

[SDL 2](https://github.com/libsdl-org/SDL/tree/SDL2)

## Notes

For the .exe to launch on Windows as is, you need to copy the SDL `SDL2.dll` file to the build folder containing the 
`SDLTest.exe` file prior to executing the `.exe`.
