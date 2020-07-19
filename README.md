# Get_Next_Line

Reading a line on a file descriptor is way too tedious. The aim of this project is to code a function that returns a line ending with a newline, read from a file descriptor without knowing it's size beforehand. It incorporates static variables and allows a deeper understanding of memory allocations, either heap or stack. It explores the unexpected complexity within the use of one or many static variables as well as the life cycle of a buffer, including manipilation.

### Requirements

-gcc compiler

### Compiling

#### Run the following commands:
* To compile
    * make
* To remove objects:
    * make clean
* To remove objects and binary file:
    * make fclean
* To re-compile:
    * make re

### Executing

* Clone/download the repository
    * git clone --recursive (url)
* cd src/
* Compile with main.c:
    * gcc get_next_line.c main.c
* Run program:
    * ./a.out (some test)
    