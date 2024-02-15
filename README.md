# IMOU-Ranger-2D-firmware
Imou Ranger-2D firmware zip file extracted while firmware upgrade

The zip firmware file was extracted using the famous wireshark utility

The zip file can  be analyzed for reverse engineering and other ethical purposes.

                  REASON BEHIND ALL THIS....

Few years ago, I bricked an Imou IP camera during a firmware upgrade process and was 
unable to find any guide or any firmware file of that camera on the INTERNET for 
recovery purpose.
I was very frustrated...

Few months ago, I bought a new IMOU IP camera, and proceeded as follows-

1. Made a hotspot using my computer and connected the camera using the PC hotspot
2. set-up and ran wireshark and started listening to packets on my wifi
3. Opened the IMOU-Life app on my phone which was also connected to my PC hotspot
4. After a notification in the app that a firmware upgrade is available, I initiated the download process
5. After firmware upgrade completed, I saved the captured file and extracted the firmware payload.


                     THIS IS A SMALL STEP

 After extracting the zip file, I
 found that the firmware is divided into several image files in partitions like "kernel", "boot" etc
 and along with these there is a file which is a shell script to flash these image files to respective partitions

 I have uploaded all the other files after extraxting the zip file which can be further unpacked by utilitues like 'unsquashfs' to unpack the squashfs linux file system. 

 
   I am not a pro-hacker but I strive to be one, I have just taken the ONE step which was not taken
   when I encountered my problem with this chinese camera.

   ALL help is WELCOME ...... "Hackers"
                  
