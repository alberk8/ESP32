# nanoFramework ESP32 Custom Build
The build is based in IDF 4.4.1 with latest [nf-interpreter](https://github.com/nanoframework/nf-interpreter.git) hash 3c0351642bf6349f3fca08b2cafabc38db62ab30 

## How to Deploy firmware
1) copy the nanoCLR.bin for the bin directory of this repo to temporary directory.  
   In the example it is placed in c:\temp.   You must use the fullpath regardless of whether 
   you have switched (cd) to the target directory.

c:\> nanoff --target ESP32_REV0 --update --serialport COM6 --clrfile "c:\temp\nanoclr.bin"

