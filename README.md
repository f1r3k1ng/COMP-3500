# COMP-3500
## Operating Systems
#### Instructor: Mark Yampolskiy
#### Grade Received: A
### Project Specification

For this project we were instructed to make some simple insructions to interact with a simulated filesystem. In order to simulate a file system we used a binary file. The four functions we created are as follows. First, is an *EraseSector* function which will erase an entire sector or block of the file system. Second, an *EraseAllSectors* which will completely wipe the entire file. Third, we have the *ReadWord* function, as per our instructions this function is only allowed to read a word if the starting address of that word is even. Lastly, we have the *WriteWord* function which writes a word starting from a specific address, like the *ReadWord* function the start of the address must be even. Additionally we were only allowed to use bitwise &, the point of these four functions was not to be optimal solutions but solutions that required us to think outside the box in further development of our filesystem.
