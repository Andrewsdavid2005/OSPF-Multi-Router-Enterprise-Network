# OSPF Multi-Router Enterprise Network

A Cisco Packet Tracer enterprise networking project demonstrating
multi-router OSPF routing, LAN connectivity, dynamic route learning,
passive interfaces, router IDs, and network redundancy through an
alternate routing path.

---

## Project Overview

The **OSPF Multi-Router Enterprise Network** is a simulated enterprise
network built using Cisco Packet Tracer.

The network consists of three routers connected in a triangular topology.
Each router provides connectivity to a separate LAN.

OSPF (Open Shortest Path First) is configured as the dynamic routing
protocol so that all routers can automatically learn routes to remote
LAN networks.

The triangular topology also provides redundancy. If one router-to-router
link fails, OSPF can calculate an alternate path through the remaining
router.

---

## Project Objectives

The main objectives of this project are:

- Understand OSPF dynamic routing
- Configure multiple Cisco routers
- Configure OSPF Area 0
- Configure OSPF Router IDs
- Configure router-to-router links
- Configure LAN networks
- Configure passive interfaces
- Verify OSPF neighbor relationships
- Verify dynamically learned routes
- Test end-to-end connectivity
- Simulate router-link failure
- Observe automatic route convergence
- Understand redundant enterprise network design
- Troubleshoot OSPF connectivity problems

---

# Network Architecture

The network contains three enterprise locations:

```text
                         R1
                      /     \
                     /       \
                  R2 -------- R3
                  |            |
                 SW2          SW3
               /     \       /    \
             PC3     PC4   PC5    PC6

                  |
                 SW1
                /   \
              PC1   PC2
