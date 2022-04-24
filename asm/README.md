
# Linux
```bash
nasm -f elf64 hello.asm -o hello.o
ld hello.o -o hello
./hello

```

`objdump --disassemble-all hello`


; /usr/local/bin/nasm -f macho64 64.asm && ld -macosx_version_min 10.7.0 -lSystem -o 64 64.o && ./64


https://markkevinbaltazar.medium.com/how-to-compile-link-and-build-a-c-program-using-gcc-578071c79a76
https://medium.com/@thisura1998/hello-world-assembly-program-on-macos-mojave-d5d65f0ce7c6
