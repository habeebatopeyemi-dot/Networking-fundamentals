# Networking-fundamentals

1. OSI Model Layers

> Application Layer:Interface between user applications and network services.Examples; web browsers and apps like Zoom.

> Presentation Layer:Translates and formats data so different systems can understand it.Handles encryption and compression.

> Session Layer:Manages and maintains communication sessions between devices.Supports session checkpoints and recovery. Example;secure banking sessions.

> Transport Layer:Provides end to end communication, ensuring reliable data transfer. Handles error recovery and flow control.
Example; TCP (Transmission Control Protocol).

> Network Layer:Responsible for routing and logical addressing.
Determines the path data takes across networks.Example; IP (Internet Protocol).

> Data Link Layer:Handles node to node data transfer and error detection on the same network.
Example; Ethernet switches.

> Physical Layer:Deals with physical connections and hardware transmission of data. Example;   Wi-Fi.

2. Subnet Calculation
   
IP Address: 192.168.1.0

CIDR: /26

Block Size: 64

> Subnet 1

Network Address: 192.168.1.0

First Host: 192.168.1.1

Last Host: 192.168.1.62

Broadcast: 192.168.1.63

> Subnet 2

Network Address: 192.168.1.64

First Host: 192.168.1.65

Last Host: 192.168.1.126

Broadcast: 192.168.1.127

> Subnet 3

Network Address: 192.168.1.128

First Host: 192.168.1.129

Last Host: 192.168.1.190

Broadcast: 192.168.1.191

3. TCP/IP Protocol Suite (Example Loading a Web Page)

> Application Layer:Browser sends an HTTP request to a web server.

> Transport Layer:TCP establishes a reliable connection.

> Internet Layer:Handles logical addressing and routing using IP.

> Network Access Layer
Manages the physical transmission of data through network hardware.
