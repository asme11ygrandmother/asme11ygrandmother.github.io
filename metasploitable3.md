**This is my metasploitable 3 page**

1. The first thing I had to do was figure out the machine's IP using netdiscover:

![Image](images/mtsplt3/wt1/netdiscover.png)

2. I like to perform full port scans to be sure that I don't miss anything; I dont like using nmap for this because it frequently takes too long. I have modified a script to do this task and print the open ports in a consistent manner of time:

![Image](images/mtsplt3/wt1/fullportscan.png)