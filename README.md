# VLAN and Inter-VLAN Routing Lab

## Objective

Configure separate VLANs and allow communication between them
through a router.

## Equipment

- One Cisco router
- Two Cisco switches
- Four computers
- Cisco Packet Tracer

## VLANs and Addressing

| VLAN | Department | Network |
|---|---|---|
| 10 | Administration | 192.168.10.0/24 |
| 20 | Support | 192.168.20.0/24 |

## Configuration

Commands used to create the VLANs, configure trunk ports,
and enable inter-VLAN routing.

## Verification

- `show vlan brief`
- `show interfaces trunk`
- `show ip interface brief`
- `ping`

## Problems Encountered

The computers initially could not communicate because the switch
port was assigned to the wrong VLAN.

## What I Learned

I learned how access ports, trunk ports, and router subinterfaces
work together.
