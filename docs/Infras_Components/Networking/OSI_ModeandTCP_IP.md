# OSI Model and TCP/IP Model

## OSI Model

The OSI (Open Systems Interconnection) model is a conceptual framework used to understand and standardize the functions of a telecommunication or computing system without regard to its underlying internal structure and technology. The model is divided into seven layers:

1. **Physical Layer**: Transmits raw bit streams over a physical medium.
2. **Data Link Layer**: Handles error detection and correction from the physical layer, and frames data packets.
3. **Network Layer**: Manages packet forwarding including routing through different routers.
4. **Transport Layer**: Provides reliable data transfer services to the upper layers.
5. **Session Layer**: Manages sessions between applications.
6. **Presentation Layer**: Translates data between the application layer and the network format, including encryption and decryption.
7. **Application Layer**: Supports application and end-user processes, such as HTTP and FTP.

## TCP/IP Model

The TCP/IP (Transmission Control Protocol/Internet Protocol) model, also known as the Internet protocol suite, is a more practical model used for network communications. It has four layers:

1. **Link Layer**: Corresponds to the OSI physical and data link layers; handles physical addressing and access to the medium.
2. **Internet Layer**: Maps to the OSI network layer; handles logical addressing, routing, and packet forwarding (e.g., IP).
3. **Transport Layer**: Similar to the OSI transport layer; provides host-to-host communication services for applications (e.g., TCP, UDP).
4. **Application Layer**: Combines the OSI session, presentation, and application layers; supports end-user services and applications (e.g., HTTP, FTP, SMTP).

## Comparison

- **Layers**: The OSI model has 7 layers, while the TCP/IP model has 4 layers.
- **Development**: The OSI model is a theoretical model used as a teaching tool, while the TCP/IP model is a practical model used in real-world networking.
- **Protocol Dependency**: The OSI model is protocol-independent, while the TCP/IP protocols were developed before the model.
- **Usage**: The OSI model provides a universal set of standards, while the TCP/IP model is used specifically for the suite of protocols on the Internet.


