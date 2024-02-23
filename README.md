# Based off Cache Lab from UChicago CMSC 15400: Intro to Computer Systems (and Carnegie Mellon)

## About:
A cache simulator implemented in C for my computer systems class. 
The simulator takes a Valgrind trace file as input as well as parameters
for the cache and accurately outputs the expected number of hits, misses, 
and evictions for the trace file. 

To compile, run:
    `linux> make`

To test correctness of simulator, run:
    `linux> ./test-csim`

## Files:

1. csim.c : Cache simulator  
2. Makefile : Builds the simulator and tools  
3. README : This file  
4. csim-ref* : The executable reference cache simulator  
5. test-csim* : Tests your cache simulator  
6. traces/ : Trace files used by test-csim.c  
