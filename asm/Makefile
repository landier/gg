build:
	nasm -f macho64 hello.asm

link:
	ld -macosx_version_min 10.7.0 -o hello hello.o

run:
	./hello
