# HELLO WORLD

A simple "HELLO WORLD" program for the Game Boy.

## References

* [https://gbdev.io/gb-asm-tutorial/index.html](https://gbdev.io/gb-asm-tutorial/index.html)

## Build

    rgbasm -o hello-world.o hello-world.asm
    rgblink -o hello-world.gb hello-world.o
    rgbfix -v -p 0xFF hello-world.gb
