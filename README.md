# choppa
Shellcode chopper
This is a simple tool to chop up shellcode. I previously did a challenge that required using write primitives to copy over shellcode to a memory location in  smal chunks. You could implement the same process in a python exploit using loops to make it more streamlined and a smaller file size or you can use this to spit out your write/what/where with shellcode in 8-byte chunks. I also updates an offset variable by 8-bytes to put each chunk in order and not overwrite each other. Chunk size and functions/variables can all be edited to meet the needs of the challenge being worked.
![image](https://github.com/ApexPredator-InfoSec/choppa/assets/84335647/df05e44f-8f71-4650-8738-01cbcdf6ac82)
