# Subnetting

Subnetting is a process used to divide a single IP network into multiple smaller, more manageable sub-networks or subnets. This allows for better utilization of IP addresses and improved network security and performance.

## Why Subnetting?

1. **Efficient IP Address Utilization**: Helps avoid wastage of IP addresses.
2. **Improved Network Performance**: Reduces network congestion by limiting broadcast domains.
3. **Enhanced Security**: Segments the network to limit access to sensitive parts.
4. **Simplified Management**: Makes large networks more manageable and organized.

## Subnet Mask

A subnet mask is used to divide an IP address into network and host portions. It determines which part of the IP address is used for the network and which part is used for hosts within that network.

### Example:

For IP address `192.168.1.0` with subnet mask `255.255.255.0`:
- **Network Portion**: `192.168.1`
- **Host Portion**: `0`

## Calculating Subnets

### Steps to Subnet:

1. **Determine the Number of Subnets Needed**: Decide how many subnets are required for your network.
2. **Calculate Subnet Mask**: Based on the number of required subnets, calculate the new subnet mask.
3. **Determine Subnet Addresses**: Identify the network addresses for each subnet.

### Subnet Calculation:

1. **Convert IP Address to Binary**: `192.168.1.0` -> `11000000.10101000.00000001.00000000`
2. **Apply Subnet Mask**: Extend the subnet mask to cover the number of subnets needed.
   - For 4 subnets, you need 2 additional bits (2^2 = 4).
   - New Subnet Mask: `255.255.255.192` -> `11111111.11111111.11111111.11000000`
3. **Calculate Subnet Ranges**:
   - Subnet 1: `192.168.1.0` - `192.168.1.63`
   - Subnet 2: `192.168.1.64` - `192.168.1.127`
   - Subnet 3: `192.168.1.128` - `192.168.1.191`
   - Subnet 4: `192.168.1.192` - `192.168.1.255`

### Number of Hosts per Subnet:

To calculate the number of usable hosts per subnet, use the formula:

(2^(32 - subnet mask bits)) - 2

For a subnet mask of `/26` (255.255.255.192):
- Usable hosts = `2^(32 - 26) - 2 = 62`

## VLSM (Variable Length Subnet Masking)

VLSM allows for more efficient use of IP addresses by using different subnet masks within the same network. This is useful when subnets of various sizes are needed.

### Example:

1. **Larger Subnet**: `192.168.1.0/25` -> `192.168.1.0 - 192.168.1.127` (126 hosts)
2. **Smaller Subnet**: `192.168.1.128/26` -> `192.168.1.128 - 192.168.1.191` (62 hosts)
3. **Even Smaller Subnet**: `192.168.1.192/27` -> `192.168.1.192 - 192.168.1.223` (30 hosts)

## Tools and Resources

- **Subnet Calculators**: Online tools that automate subnet calculations.
- **IP Subnetting Guide**: Detailed guides and tutorials on subnetting principles.

For more detailed information, refer to the [Subnetting Guide](https://en.wikipedia.org/wiki/Subnetwork) on Wikipedia.

