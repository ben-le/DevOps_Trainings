# IPv4 & IPv6 Protocols

## IPv4 (Internet Protocol version 4)

IPv4 is the fourth version of the Internet Protocol, widely used to identify devices on a network through an addressing system. IPv4 uses a 32-bit address scheme, allowing for a total of 4.3 billion unique addresses.

### Key Features

1. **Address Format**:
   - IPv4 addresses are written in decimal format, divided into four 8-bit fields separated by periods (e.g., 192.168.1.1).

2. **Header Size**:
   - The IPv4 header is 20-60 bytes in size, depending on the use of options.

3. **Address Space**:
   - Provides approximately 4.3 billion unique addresses.
   - Subnetting and Classless Inter-Domain Routing (CIDR) help efficiently use the address space.

4. **Security**:
   - Limited built-in security features.
   - Relies on additional protocols like IPsec for encryption and secure communication.

### Limitations

1. **Address Exhaustion**:
   - The rapid growth of the internet has led to the exhaustion of available IPv4 addresses.

2. **Fragmentation**:
   - IPv4 networks often require Network Address Translation (NAT) to connect multiple devices using a single public IP address.

## IPv6 (Internet Protocol version 6)

IPv6 is the latest version of the Internet Protocol, designed to address the limitations of IPv4. IPv6 uses a 128-bit address scheme, providing an almost limitless number of unique addresses.

### Key Features

1. **Address Format**:
   - IPv6 addresses are written in hexadecimal format, divided into eight 16-bit fields separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

2. **Header Size**:
   - The IPv6 header is 40 bytes in size, with simplified fields compared to IPv4.

3. **Address Space**:
   - Provides approximately 340 undecillion unique addresses.
   - Eliminates the need for NAT, allowing direct end-to-end connectivity.

4. **Security**:
   - Includes built-in support for IPsec, ensuring confidentiality, integrity, and authenticity of data.

5. **Auto-Configuration**:
   - Supports both stateless and stateful address configuration.
   - Simplifies network configuration through features like SLAAC (Stateless Address Autoconfiguration).

### Advantages

1. **Scalability**:
   - Vast address space accommodates the growing number of internet-connected devices.

2. **Efficiency**:
   - Simplified header structure improves routing efficiency and performance.

3. **Security**:
   - Enhanced security features with mandatory support for IPsec.

4. **Mobility**:
   - Improved support for mobile devices and seamless transition between networks.

## Comparison

| Feature       | IPv4                           | IPv6                           |
|---------------|--------------------------------|--------------------------------|
| Address Size  | 32-bit                         | 128-bit                        |
| Address Format| Decimal (e.g., 192.168.1.1)    | Hexadecimal (e.g., 2001:0db8:85a3::8a2e:0370:7334) |
| Header Size   | 20-60 bytes                    | 40 bytes                       |
| Address Space | 4.3 billion addresses          | 340 undecillion addresses      |
| Security      | Relies on IPsec                | Built-in IPsec support         |
| Auto-Config   | Requires manual or DHCP config | Supports stateless and stateful auto-config |

For more detailed information, refer to the [IPv4](https://en.wikipedia.org/wiki/IPv4) and [IPv6](https://en.wikipedia.org/wiki/IPv6) pages on Wikipedia.
