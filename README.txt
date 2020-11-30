Jessica Cheng

This is my implementation of malloc, realloc, and free, which uses a doubly-linked, explicit free list. I achieved good results when compared against Linux’s implementation of C malloc in terms of time efficiency because I found free space via first-fit, which means the first free block that would accomodate the malloc request will be used.

