Install C Compiler (GCC)
   sudo apt update
   sudo apt install build-essential -y

Check GCC Version
   gcc --version

Compile and Run a C Program
   Create file:
      nano program.c

Sample code:
         #include <stdio.h>

         int main() {
              printf("Hello from C!\n");
              return 0;
          }

Compile:
   gcc program.c -o program

Run:
   ./program
