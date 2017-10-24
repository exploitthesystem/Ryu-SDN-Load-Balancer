# Ryu-SDN-Load-Balancer
A simple load balancing controller that utilizes the Ryu SDN framework to program a network switch.

# Author: Marko Ljubicic

Implemented in Python 2.7.

This application was written using the Ryu SDN framework to shape OpenFlow network traffic. It was used to
control a simple network topology with a single switch and five hosts, two of which represented servers.
The controller programmed the switch to alternate traffic between the servers in a round-robin selection scheme.
The network infrastucture was constructed using the Mininet network emulator.
