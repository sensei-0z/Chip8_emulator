# Chip8_emulator
A CHIP-8 emulator in C++

HIP-8, a programming language created by Joseph Weisbecker in the 1970s, was designed to simplify game development on early microcomputers like the COSMAC VIP and Telmac 1800. CHIP-8 programs are executed using a virtual machine, a software simulation of a computer. 
This implementation of a CHIP-8 virtual machine is quite comprehensive but currently lacks sound capabilities.

## Compiling and Running

Requires cmake and SDL2:
```
 sudo apt-get install cmake libsdl2-dev
```

Compile:
```
 mkdir build
 cd build
 cmake ..
 make
```

Run:
```
./chip8 ../roms/PONG
```
1 (public domain) ROM is included in the `roms` directory.

## References
Some helpful resources I used when writing this

- https://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/
- https://en.wikipedia.org/wiki/CHIP-8
- https://austinmorlan.com/posts/chip8_emulator/
