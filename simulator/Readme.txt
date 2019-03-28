Comiple Rule:
gcc -o icpu simulator-interrupt.c -Wall
./assembler 4p-os.asm ios
./icpu ios 30

Description: 
assembler is to transform the assembly code to machine code. So icpu can run this code.
