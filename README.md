# Ethical-Hacking-Assignment-
Scapy Overview
Ethical Hacking Assignment
SCAPY TOOL
First we need to be a super user to aviode being denied access as a low level user
 sudo su
Gives you a super user previllage
scapy
sniff()
I now open a new terminal and ping google.com
ctrl + c (to stop on ping terminal)
I will also stop the sniff in the previous terminal by holding ctrl +c (to stop sniffing on scapy terminal)
I will run paro=_ and followed by paro.summary() to see the details of my captured traffic
sniff(iface="br-internal")
AT this my vm/ attacker Machine could find the interface
But as per the steps
I understood it all and below are the rest of them without screen-shoot
 We ping this domain and 10.6.6.1/24
 Open browser and type 10.6.6.23
 ctrl +c to stop sniffing
 paro2=_  paro2.summary()
 sniff(iface="br-internal" ,filter ="icmp",count=5)
 ping 10.6.6.23
 ctrl +c (to stop on ping terminal)
 ctrl +c (to stop on scapy terminal)
 paro3=_  paro3.summary()
 paro3[3]
