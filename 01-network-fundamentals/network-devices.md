# Network Devices – Roles and Responsibilities

## Why this exists
Networks are built from specialized devices, each responsible for handling traffic at different layers. Separating these roles makes networks faster, more scalable, and easier to troubleshoot.

## When it breaks / goes wrong
- Devices used outside their intended role
- Bottlenecks caused by incorrect placement
- Broadcast storms due to lack of segmentation
- Traffic reaching a device that cannot interpret it

## How I would tell
- Excessive flooding or collisions
- Traffic not reaching other networks
- High latency despite good link speed
- Packets dropped at network boundaries

## One thing I keep forgetting
Not all network devices understand the same type of data. Frames, packets, and bits are handled by different devices.

## Mental model
A network is an assembly line. Each device only performs the task it was designed for and passes the traffic to the next station.

## Notes / Open questions
How multilayer switches blur the line between switching and routing.
