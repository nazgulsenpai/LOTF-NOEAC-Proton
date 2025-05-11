# Launch Lords of the Fallen (2023) without Easy Anti-Cheat in Proton/Linux
Super simple program to launch Lords of the Fallen without EAC (for modding) for those using Proton/Linux

To use, rename the LOTF2.exe in the folder and replace it with this exe. 

To build, you will need the Nim compiler and your distributions mingw32 x64 cross compiler (on Void Linux it's cross-x86_64-w64-mingw32 for example).

`nim c -d:mingw32 -d:release LOTF2.nim`
