# Chip8_emulator
A CHIP-8 emulator in C++

CHIP-8 is an interpretted programming language developed by Joseph Weisbecker in the mid 70s and was initally used on the COSMAC VIP and Telmac 1800 8-bit microcomputers to make game programming easier. CHIP-8 programs are run using a CHIP-8 virtual machine.

This is a fairly complete implementation of a CHIP-8 virtual machine however there is currently no sound.

## Compiling and Running

Requires cmake and SDL2:
```
$ sudo apt-get install cmake libsdl2-dev
```

Compile:
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```

Run:
```
./chip8 <ROM file>
```
23 (public domain) ROMs are included in the `roms` directory.

## References
Some helpful resources I used when writing this

- https://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/
- https://en.wikipedia.org/wiki/CHIP-8
- https://austinmorlan.com/posts/chip8_emulator/
