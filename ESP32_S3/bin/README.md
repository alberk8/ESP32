# ESP32 S3 firmware without PSRAM
1) create a directory on your PC.  In this exmaple I am using c:\temp

2) Download the nanoCLR.bin to the directory.

3) Flash the firmware
nanoff --target ESP32_S3 --update --serialport COM14 --clrfile "c:\temp\nanoCLR.bin"

# ESP32 S3 BLE firmware without PSRAM
1) create a directory on your PC.  In this exmaple I am using c:\temp

2) Download the nanoCLR_S3_BLE.bin to the directory.

3) Flash the firmware
nanoff --target ESP32_S3_BLE --update --serialport COM14 --clrfile "c:\temp\nanoCLR_S3_BLE.bin"