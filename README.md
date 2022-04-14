# CSAPP_labs
Lab works for the 3rd Edition CSAPP.

Sources from http://csapp.cs.cmu.edu/3e/labs.html

I seek my Chinese version of CSAPP for help. 

Issue encountered:

1. Compiling error 

When trying to compile bits.c in datalab, something went wrong with *#include <btis/libc-header-start.h>*.

It's because the missing of the libraries for m32 on the machining running this code. The solution is to download the libraries. 

For ubuntu users, visit https://askubuntu.com/questions/91909/trouble-compiling-a-32-bit-binary-on-a-64-bit-machine
