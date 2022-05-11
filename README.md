# nanoFramework ESP32 Custom Build
The build is based in IDF 4.4.1 with latest [nf-interpreter](https://github.com/nanoframework/nf-interpreter.git) 
- Source Date: 11-May-2022
- Compile Date: 11-May-2022

## How to Deploy firmware
1) copy the nanoCLR.bin for the bin directory of this repo to temporary directory.  
   In the example it is placed in c:\temp.   You must use the fullpath regardless of whether 
   you have switched (cd) to the target directory.

c:\> nanoff --target ESP32_REV0 --update --serialport COM6 --clrfile "c:\temp\nanoclr.bin"

