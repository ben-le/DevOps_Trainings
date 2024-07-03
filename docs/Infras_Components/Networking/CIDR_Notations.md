# CIDR Notations

Classless Inter-Domain Routing (CIDR) is a method for allocating IP addresses and routing Internet Protocol packets. CIDR replaces the old system based on classes A, B, and C and offers more efficient IP address allocation.

## CIDR Notation

CIDR notation is a compact representation of an IP address and its associated network mask. It is written as follows:

<IP Address>/<Prefix Length>


For example: `192.168.1.0/24`

- **IP Address**: This is the base IP address.
- **Prefix Length**: This indicates the number of bits in the subnet mask that are set to '1'. 

## How CIDR Works

In CIDR, the IP address is divided into two parts:
- **Network Part**: The initial bits that define the network. The number of bits is indicated by the prefix length.
- **Host Part**: The remaining bits that identify a specific device (host) within that network.

### Example:

For `192.168.1.0/24`:
- **Network Part**: 192.168.1 (24 bits)
- **Host Part**: 0 (8 bits for host addresses)

## Benefits of CIDR

1. **Efficient Use of IP Addresses**: CIDR allows for IP address allocation that better fits the size of a network, reducing wastage.
2. **Reduced Routing Table Size**: CIDR helps in the aggregation of routing entries, which simplifies the routing table.
3. **Improved Network Management**: Provides more flexible and hierarchical network management.

## Calculating CIDR

### Subnet Mask Calculation

To calculate the subnet mask for a given CIDR notation:
- Convert the prefix length into a subnet mask.
- For `/24`, the subnet mask is `255.255.255.0`.

### Number of Hosts

To calculate the number of hosts within a CIDR block:
- Use the formula `2^(32 - prefix length) - 2`.
- For `/24`, `2^(32 - 24) - 2 = 254 hosts`.

## Common CIDR Blocks

- `/8` – 16,777,214 hosts (e.g., 10.0.0.0/8)
- `/16` – 65,534 hosts (e.g., 172.16.0.0/16)
- `/24` – 254 hosts (e.g., 192.168.1.0/24)

For more detailed information, refer to [CIDR Notation](https://en.wikipedia.org/wiki/Classless_Inter-Domain_Routing) on Wikipedia.
