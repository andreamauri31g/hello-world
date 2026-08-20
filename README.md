# HELLO WORLD

A simple "HELLO WORLD" program for the Game Boy.

## References

* [GB ASM Tutorial](https://gbdev.io/gb-asm-tutorial/index.html)
* [RGBDS](https://rgbds.gbdev.io/) (a free assembler/linker package for the Game Boy and Game Boy Color)

## Build

    rgbasm -o hello-world.o hello-world.asm
    rgblink -o hello-world.gb hello-world.o
    rgbfix -v -p 0xFF hello-world.gb

