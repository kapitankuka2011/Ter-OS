# TerOS

is a operating system.

# Running it

Requirements:
- Qemu
- Qemu added to path
- Iso file (in out directory)

Linux:
    ```make run```

Windows:
    ```qemu-system-x86-64 out\TerOS.iso```

# Compiling

Requirements:

- Linux
- Make command
- GCC/G++
- nasm
- grub-mkrescue
- LD command

First we need to compile the source code<br />
    ```make```
<br /><br />and when its done you are done with the compiling to tun it use:<br />
    ```make run```
<br /><br />then you can clean up a bit:<br />
    ```make clean```

if you are on windows then maybe try wsl
