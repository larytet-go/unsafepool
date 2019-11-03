# unsafepool

Unsafe pool's New() alocates the specified number of memory blocks. 
The raw memory block is large enough to fit object of the specified type. 
The pool's Alloc()/Free() API operates with pointers to the blocks (at this point Go crowd runs away crying to things like https://github.com/patrickmn/go-cache). 
