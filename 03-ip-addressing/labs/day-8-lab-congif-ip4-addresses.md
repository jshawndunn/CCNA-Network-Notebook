# Day 8 Lab – Connecting Devices

## Lab Source
Packet Tracer file provided by Jeremy’s IT Lab.  
Used for hands-on practice and observation.

## Goal
View and configure IP addresses on router interfaces.

## What I Did
- Viewed interface information
- Configured IP addresses on R1’s interfaces
- Enabled interfaces
- Added descriptions to interfaces
- Viewed and saved the running configuration
- Configured IP addresses on PC1, PC2, and PC3
- Used ping to verify connectivity

## What I Observed
- Cisco router interfaces are "administratively down" by default
- "Status" reflects the Layer 1 state
- "Protocol" reflects the Layer 2 state
- When configuring IP addresses on PCs, Packet Tracer automatically suggested a subnet mask based on the classful default for that IP address

## What I’m Not Fully Sure About Yet

## Commands Used
Commands executed during the lab to complete the required tasks.

- show ip interface brief
- interface <interface-name>
- ip address <ip-address> <subnet-mask>
- no shutdown
- description <text>
- show interfaces
- show interfaces description

## Related Lesson
Jeremy’s IT Lab – Day 7 and 8
