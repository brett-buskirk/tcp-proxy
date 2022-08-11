# TCP Proxy #

Basic Python TCP proxy to help with understanding unknown protocols, modify traffic being sent to an application, and create test cases for fuzzers. There are four main functions to consider:

1. Need to display the communication between the local and remote machines to the console.
2. Need to receive data from an incoming socket from either the local or remote machine.
3. Need to manage the traffic direction between remote and local machines.
4. Need to set up a listening socket and pass it out to the proxy handler.
