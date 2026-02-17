# Switch Interfaces (Day 9)

## Why this exists
Switch interfaces provide the physical and logical connection points between devices in a LAN. Each interface is responsible for sending and receiving Ethernet frames.

Understanding interfaces is necessary to control how devices connect to the network and how frames enter and leave a switch.

## When it breaks / goes wrong

## How I would tell

## One thing I keep forgetting

## Mental model
Each switch port is its own doorway into the network.  
Traffic entering one port is evaluated and forwarded out other ports based on the MAC address table.

An interface can be administratively disabled even if the physical cable is connected.

## Notes / Open questions
- Are not administratively down by default like Cisco routers
- If the connected device doesn't have auto-detection set and the interface does, it will attempt to figure out the speed/duplex. If the speed is 10 or 100, it will default to half-duplex. This could result in collisions if the connected host is set to full-duplex.
