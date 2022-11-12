# Client-Server Application Architecture

Client-Server application architecture is
a [network application architecture](network.md) in which there are two components (network node types), client and server. Client send
requests to server, and servers process them and return the corresponding responses.

```mermaid
flowchart LR
Client--requests-->Server
Server--responses-->Client
```

Naturally, this architecture leads
to the [2-tier architecture](2-tier.md), where client and server are deployed on different machines.