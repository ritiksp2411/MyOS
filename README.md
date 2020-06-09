# MyOS
This project is building OS from scratch which have fuctionality of booting and hardware communication on behalf of patial fulfilment of the course Operating System.


- [x] kernel.cpp - contains the functions to be executed on booting
- [x] loader.s - contains instructions on how to load the kernel.cpp and also allocates space for kernel_stack
- [x] linker.ld - links loader.o and kernel.o to create an executable .bin file
- [x] Makefile - provides instructions and parameters to convert .cpp, .s files to .o files

## To run:
To run this project type "make run" after moving inside the folder of the cloned repo.

## Another Way:

# Creating .o files
``` 
make loader.o
make kernel.o
```
# Creating .bin files
```
make mykernel.bin
make install
```
make install - to install the executable file

# To boot..

Install VirtualBox and create a new VM with 
Name: My Operating System <br />
Folder: (usually selecting the default folder specified works!) <br />
Type: Other <br />
Version: Other/Unknown
<br />
<br />
RAM selected: default<br />
Don't add virtual hard-disk<br />
On powering on your VM load mykernel.iso 
