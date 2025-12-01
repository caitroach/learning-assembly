# learning-assembly
My first few assembly programs...

# testing.asm
This is my "hello world" program in fedora KDE! 

## to run 
ensure you have `nasm` and `ld` by running `nasm -v` and `ld -v`. 

create the executable with `nasm -f elf32 -o testing.o testing.asm`
navigate to the file `ld -m elf_i386 -o testing testing.o

now run it with `/.testing` and you should get:

`Hello world :3` in your terminal! great success
