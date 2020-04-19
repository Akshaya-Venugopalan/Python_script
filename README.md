# Python_script
This is script is written for my Assignment.



This code is done based on the references from the github.Here we were asked to create a GUI(a prettyTable )which has 6 different options where we can perform the basic of pentesting activities.
About the Predefined libraries used in my code.

About prettyTable 
PrettyTable is a Python library for generating simple ASCII tables. It was inspired by the ASCII tables used in the PostgreSQL shell psql. We can control many aspects of a table, such as the width of the column padding, the alignment of text, or the table border. We can sort data. 

So i have imported the existing PrettyTable library and am using it for my GUI page creation.
import prettytable
This creates a PrettyTable with the add_row() method.
from prettytable import PrettyTable

Socket : 
 In the case of the server, you will bind a socket to some port on the server (localhost). In the case of a client, you will connect a socket to that server, on the same port that the server-side code is using.(Here i am using it for the Nmap port scanning)

Subprocess: 
 subprocesses is to use the run() function for all use cases it can handle 

Sys : 
The sys module provides information about constants, functions and methods of the Python interpreter ( here using it for the system version) 

os : 
OS module provides allows you to interface with the underlying operating system that Python is running on – be that Windows, Mac or Linux.Here This method is implemented by calling the Standard C function system(), and has the same limitations. If command generates any output, it is sent to the interpreter standard output stream.

datetime: 
to know the time of running that particular scenario.

Scapy
Here am using it to sniff the networking packets. Python function applied to each packet to determine if further action may be done. –Ex: lfilter ... opened_socket – provide an object (or a list of objects) ready to use .recv() on.

Threading : 
Allows to run the different parts of the program concurrently. 

Beautifulsoup :
We import the BeautifulSoup class from the bs4 module. The BeautifulSoup is the main class for doing work.

argparse :
The argparse module includes tools for building command line argument and option processors. 

The above of the someof the bulit in libraries available in python and i have used them here 

For all the 6 cases i have taken reference from github and been commented in the code aswell so that you can have and idea of it. 

References : 

reference with subscription for packpub  "https://subscription.packtpub.com/book/networking_and_servers/9781784399771/7/ch07lvl1sec43/pyshark"

Reference "https://github.com/j2sg/johnny"

reference from https://www.pyimagesearch.com/2015/10/12/scraping-images-with-python-and-scrapy/

reference https://gist.github.com/kf4bzt/ff0b499821c12722341dbdbde3f57e60

reference 'https://github.com/teknogeek/virtual-host-discovery-py/blob/master/scan.py' 

