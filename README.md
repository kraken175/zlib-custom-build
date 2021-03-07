# zlib-custom-build

This is the custom build of the zlib compression library.

It contains:
- CRC32C table instead of CRC32
- CRC32C polynomial instead of CRC32
- Preconfigured Ninja file to build with GCC
- Edited Sample Programs

The zlib custom source code can be seen in ['master'](https://github.com/iammopeio/zlib-custom-build/tree/master) branch, while [SwordFishTheChordedPlayer1](https://github.com/SFTCP1) uploaded it. so you will use CMake to build the library.

This master branch was created by [SFTCP1](https://github.com/SFTCP1), so it relies on zlib library. The steps to get the code are:
1. git clone https://github.com/iammopeio/zlib-custom-build.git
2. cd zlib-custom-build
3. git checkout master

To build a library:
1. cmake -G Ninja .
