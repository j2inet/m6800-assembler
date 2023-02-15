#Motorola 6800 Assembler

This is almost an exact copy of the repository uploaded by [JimInCa](https://github.com/JimInCA). I'm not using the same build system as him. I wanted the source code in a form that I could easily compile with Visual Studio 2022. 


You can find the original repository [here](https://github.com/JimInCA/motorola-6800-assembler). 

I've put precompiled binaries in this repository too. You can find those in the [./builds](builds) folder. 

The assembly mnemonics for the 6800 series is the same, but the binary encoding isn't necessarily identical. Though this outputs several executables for different processors in the M6800 family, the source code for each project is coming from the same set of files with difference being in which version of the file named `d0x.c` gets included (where `x` is replaced with the processor name).