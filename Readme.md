The script in this repository is used to help print out and organize the results of a pcap file for querying and review. 

This script helps to reduce the amount of time it takes in order to review tcp connection information that would be analyzed using the program wireshark.

In smaller settings the review of this data is very simple since there are a limited number of devices and network interfaces on a network. In a corporate setting though, there may be thousands of devices or interfaces which need to be monitored.

This script will take each TCP stream and report out the ip addresses of the two nodes involved, the ascii information from the tcp stream, and other networking information about the connection.

The output of this file is a txt document which can be edited and searched using a program such as VIM.

For a full breakdown line by line of what each line does and why its included. Please see my portfolio website - michaelplasekttcybersecurityportfolio.xyz

The writeup may not be available until June 13th 2023.