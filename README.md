# Troubleshooting
All the troubleshooting I have incurred in my life

1. Network Manager in centos 7 not starting
If the error is "device lo not available"
Solution:
Just open a terminal and run
***
[myuser@mycentos7 ~]$ nmcli n off 

[myuser@mycentos7 ~]$ nmcli n on

***
Reference https://access.redhat.com/discussions/6278791
