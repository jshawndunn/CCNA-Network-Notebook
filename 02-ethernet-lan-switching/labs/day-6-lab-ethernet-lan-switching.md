# Day 6 Lab – Connecting Devices

## Lab Source
Packet Tracer file provided by Jeremy’s IT Lab.
Used for hands-on practice and observation.

## Goal
Become familiar with how switches learn and forward frames when traffic is generated.

## What I Did
- Predicted what traffic would be generated when sending a ping
- Used Simulation mode to observe the traffic
- Examined MAC address tables on the switches
- Examined ARP tables on the PCs
- Cleared the MAC address tables on each switch and observed behavior again

## What I Observed
- When I sent a ping from PC1 to PC3, ARP was used to learn the destination MAC address.
- The ARP request and reply allowed the switches to learn MAC addresses from the source field of each frame.

## What I’m Not Fully Sure About Yet
- Interpreting all of the details shown in the Simulation view

## Commands used
Commands executed during the lab to complete the required tasks.

- ping
- arp -a
- show mac adress-table
- clear mac address-table dynamic

## Related Lesson
Jeremy’s IT Lab – Day 5 and 6
