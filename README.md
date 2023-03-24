#os

To Run:

    $ nasm -f bin 32bit-main.asm -o boot_loader
    $ qemu-system-x86_64 boot_loader.bin