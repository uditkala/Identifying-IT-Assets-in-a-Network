# Identifying-IT-Assets-in-a-Network
An interface for displaying all active/ inactive machines on a local network domain and display their hardware/software  information.

# Project Specifications:

The interface is used to display a list of machines within the range of provided IP addresses in a single web page where in each machine will be represented by a button or hyperlink text using color codes to distinguish each machine by OS and Up/Down Status.
Further on clicking any of the button or hyperlink representing a machine, following information about that particular machine appears:

1.	 Host name
2.	 OS name and version details
3.	 Processor details
4.	 RAM capacity
5.	 Video card details, if any
6.	 Local file system/disk drives
7.	 Mounted network file systems
8.	 Available Users
9.	 Attached Devices
10.  System Serial Number

# System Configuration : 

1.	Firewall of all the hosts and the server being used in this network should be turned off
    OR
    Necessary inbound and outbound rules must be defined so as to allow:
      a.	WMI commands (for windows to windows access/ linux to windows access)
      b.	SSH commands (for host linux or unix access) -> Implemented on windows using MOBAXTERM

2.	If the server computer is a windows running system then it should have a ssh server installed on it.
3.	This project uses a third party GUI based SSH tool called MOBAXTERM to set up a remote connection with a linux or a linux based           system.
4.	For windows to windows access there is no need for a ssh server running on the system.
5.	All the computers should be on the same network
6.	All the computers in the network should have a common username and password.
