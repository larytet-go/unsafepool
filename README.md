# unsafepool

This is a sub 3nanos memory pool in Go.

Unsafe pool's New() alocates the specified number of memory blocks. 
The raw memory block is large enough to fit object of the specified type. 
The pool's Alloc()/Free() API operates with pointers to the blocks. At this point Go crowd runs away crying.
