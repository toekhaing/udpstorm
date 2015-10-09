# udpstorm
UDP attack also called Chargen Attack. This attack uses UDP service Chargen (port 19) sends a packet of characters to UDP service echo (port 7) arrived those packet.


#Compile 

gcc -o udpstorm udpstorm.c


#usage

./udpstorm <source address> <source port> <destination address> <destination port>


