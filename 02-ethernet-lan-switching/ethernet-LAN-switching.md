## Why this exists
Provides hop-to-hop delivery of frames within a local area network.

## When it breaks / goes wrong

## How I would tell

## One thing I keep forgetting
- Ethernet operates independently of IP addressing.

## Mental model
- Hosts use MAC addresses to pass frames from one hop to the next.

## Notes / Open questions
- Routers are used to separate LANs, not switches.
- The MAC address table is used to determine which interface a frame should be forwarded out to reach the destination MAC address.
- A MAC address table entry does not guarantee the host is directly attached to that interface.
