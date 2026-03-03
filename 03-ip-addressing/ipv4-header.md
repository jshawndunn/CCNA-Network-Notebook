# IPv4 Header (Day 10)

## Why this exists
The IPv4 header contains the control information required for a packet to be delivered across networks.

While the payload carries the actual data, the header contains the fields that routers use to make forwarding decisions and manage packet handling.

## When it breaks / goes wrong

## How I would tell

## One thing I keep forgetting

## Mental model
The IPv4 header is like the shipping label on a package.  
It contains the source and destination addresses along with handling instructions that guide the packet through the network.

Routers read the header, update certain fields, and forward the packet toward its destination.

## Key Fields Introduced

- Source IP Address
- Destination IP Address
- Time To Live (TTL)
- Protocol
- Header Length
- Total Length

Each field serves a role in identifying the packet, determining how it should be handled, and ensuring it does not circulate indefinitely.

## Notes / Open questions
- Which header fields change at each hop?
- How TTL is decremented and what happens when it reaches zero.
- How the Protocol field relates to Layer 4 communication.