# AutoNMS




This release version of AutoNMS is only designed to have limited use (of up to 5 nodes, of mixed vendor types if desired).  Currently, 2 major vendors starting with 'C' and 'J', as well as a major Firewall vendor (starting with 'P') are supported.  There are many other vendors that will be supported by the full version.  

Run the parent script (AutoNMS or AutoNMS.py) on a place that has access (via ssh) to any and all of the nodes you wish to discover.  

Modify the source 'nodes.txt' file (in CSV format), specifying each new line with the following format:  <ip address>,<username>,<password1>,<optional_password2>.  Make sure this source file is in the same directory as AutoNMS.

AutoNMS will retrieve information from each device on your nodes.txt list, and use that information to 'visualize' your network in a way you've never experienced it before.  

It may be necessary to launch 'index.html' in order to display this visual representation of data.  
