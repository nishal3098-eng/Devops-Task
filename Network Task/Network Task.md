**TASK: CHECK CONNECTIVITY AND PORT STATUS**

1.Get me the IP address of a particular domain (guvi.in). How do I find my CPU/memory usage of my server?. Test the connectivity between 2 nodes?



Coomand Used:


\#for checking ip of guvi.in and connectivity:

1.ping guvi.in
2.nslookup guvi.in
2.dig guvi.in



\#For Cpu memory usage of server:
1.Top

2.free -h =for space 

#Testing connectivity between Two nodes 
1.ping -c 4 guvi.in

2.I have deployed an application in guvi.com:9000, and logs show my app is running, but I’m unable to view the page. Check whether my port is open or not ?

Command Used:

1.telnet guvi.com 9000

2.wget guvi.com:9000
3.netstat -na | grep 9000

Output:Based on netstat, telnet, and wget outputs, port 9000 is not listening and is not accessible from the network.


