# unsafepool


This is a sub-3 nanosecond memory pool in Go. The roundtrip allocation-free time is less than 5 nanoseconds.

The unsafe pool's New() function allocates the specified number of memory blocks. The raw memory block is large enough to fit an object of the specified type. 
The pool's Alloc() and Free() API operates with pointers to these blocks. At this point, the Go community runs away crying.
