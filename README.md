# Melina ( Provisional name )

## Melina is a simple Linux compatibility layer for windows

### It will to do the following :

 1. Load the binary file ( in this case a x86_64 ELF )
 2. Parse it
 3. Trace the syscalls
 4. Replace them by their Win32 equivalent
 5. Finally run the program

### How the program will be run ( 6th step )
#### One solution retained for the moment
1. Create a child process to which new instructions will be sent then executed 
