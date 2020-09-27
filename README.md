# CrowPi-blackscreen-fix

This fixes black screens when loading other Linux Distributions on to the CrowPi2 AIO Raspberry Pi Laptop. The Raspberry Pi 4 model b has two HDMI ports and often defaults to setting the one the CrowPi2 primary display to a secondary which results in a black screen. 

Attached is the config.txt that will go in the boot folder of your distribution you are loading on this laptop. 

_If loading this from another PC: You will need to mount the FAT32 EFI partition and modify the config.txt file_

Match the config.txt from what ever image you are using and you will no longer have a black screen
