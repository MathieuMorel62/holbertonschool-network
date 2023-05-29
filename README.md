# <p align="center">Holbertonschool-Network</p>

<img src="https://omedia.dev/sites/default/files/styles/blog_full/public/2021-03/networking.jpg?itok=APld8Djq" width="100%">
This project, **Networking Basics**, aims to provide a concise and comprehensive understanding of fundamental networking concepts. It covers topics such as the OSI model, different network types, IP addressing, TCP/UDP protocols, and network troubleshooting tools.
  
The project explores the **OSI model**, which consists of seven layers that define the functions and services required for network communication.
  
You will learn about **Local Area Networks (LANs)** and **Wide Area Networks (WANs)**, their typical usage scenarios, and geographical sizes.
  
The **Internet**, a global network of interconnected devices, will be discussed, along with **IP addressing** and the distinction between private and public IP addresses.
  
The project also delves into the transition from **IPv4** to **IPv6** and the benefits of the latter.
  
You will gain an understanding of **TCP and UDP protocols**, their differences, and their roles in data transfer.
  
**Ports**, which facilitate communication between applications and devices, will be covered, including the memorization of port numbers for SSH, HTTP, and HTTPS.
  
Finally, network troubleshooting tools such as `netstat` and `ping` will be introduced.
  
By the end of this project, you will have a solid understanding of networking basics and be able to explain these concepts confidently. The knowledge gained will enable you to comprehend the OSI model, differentiate between LANs and WANs, describe the Internet, identify IP addresses, understand TCP and UDP protocols, and utilize network troubleshooting tools effectively.
  
Feel free to explore the project and enhance your networking knowledge!

#### `General`

At the end of this project, you are expected to be able to [explain to anyone](https://intranet.hbtn.io/rltoken/gwuqSZXS7ElRbiObQzDcTg), **without the help of Google:**

## OSI MODEL

<details>
<summary>What is OSI Model?</summary><br>

The `Open Systems Interconnection (OSI)` model is a conceptual framework that standardizes the functions of a communication system or network into seven distinct categories, or "layers". These layers describe what happens when data is transferred over a network, moving from the application (the user-end layer) to the physical transmission medium (like ethernet cables), and then back again.
</details>
<details>
<summary>How many layers it has?</summary><br>

The `OSI Model` has seven layers. These are, from top to bottom: Application, Presentation, Session, Transport, Network, Data Link, and Physical.
</details>
<details>
<summary>How is it organized?</summary><br>

The OSI Model is organized into seven layers, each with a specific function:
  
1. `Application Layer`: This is the layer that interacts with software applications that implement a communicating component.
  
2. `Presentation Layer`: This layer transforms data to provide a standard interface for the Application layer.
  
3. `Session Layer`: Establishes, manages and terminates connections between applications.
  
4. `Transport Layer`: Provides reliable transmission of data segments, as well as the acknowledgement of the successful data transmission and re-transmits the ones that fail.
  
5. `Network Layer`: Decides on the best path for data transfer and routes the data in the network.
  
6. `Data Link Layer`: Provides node-to-node data transfer (between two devices on the same network) and also handles error correction from the physical layer.
  
7. `Physical Layer`: This layer is responsible for the physical connection between devices, including aspects like electrical signals, bit transmission, cable specifications, etc.
</details><br>

-----------------

### LAN

<details>
<summary>What is a LAN?</summary><br>

A `Local Area Network (LAN)` is a network that connects computers and other devices in a relatively small area, typically a single building or a group of buildings. Most LANs are used to connect devices in the same house, office, school or university.
</details>
<details>
<summary>Typical usage of LAN?</summary><br>

`LANs` are commonly used to facilitate communication and resource sharing among devices in close proximity. This can include sharing files, operating networked applications, sharing printers or other hardware, and accessing the internet.
</details>
<details>
<summary>Typical geographical size of a LAN?</summary><br>

A `LAN` typically spans a small area like a home, office, or group of buildings close to each other. The exact size can vary, but `LANs` are generally confined to a specific room, building, or campus.
</details><br>

---------------

### WAN

<details>
<summary>What is a WAN?</summary><br>

A `Wide Area Network (WAN)` is a network that covers a large geographical area, such as a city, country or spans even across continents. The Internet is the most well-known `WAN`.
</details>
<details>
<summary>Typical usage of a WAN?</summary><br>

WANs are used to connect `LANs` and other types of networks together, so that users and computers in one location can communicate with users and computers in other locations. Companies, universities, and government entities often use `WANs` for communication, data transfer, and collaboration.
</details>
<details>
<summary>Typical geographical size of a WAN?</summary><br>

A `WAN` covers a large geographical area, which can span a city, a country, or even the entire globe.
</details><br>

-----------------

### INTERNET

<details>
<summary>What is the Internet?</summary><br>

The `Internet` is a global network of computers and computer networks that communicate with each other using the **Internet Protocol (IP)**. It allows for a wide array of information and services, such as the inter-linked hypertext documents of the **World Wide Web (WWW)**, electronic mail, telephony, and file sharing.
</details>
<details>
<summary>What is an IP address?</summary><br>

An `IP (Internet Protocol)` address is a unique numerical label assigned to each device participating in a computer network that uses the **Internet Protocol** for communication. It serves two main functions: identifying the host or network interface, and providing the location of the host in the network.
</details>
<details>
<summary>What are the 2 types of IP address?</summary><br>

There are two types of IP addresses: `IPv4` and `IPv6`.
`IPv4 (Internet Protocol version 4)` is the fourth version of Internet Protocol. It uses a 32-bit address scheme allowing for a total of just over 4 billion unique addresses.

`IPv6 (Internet Protocol version 6)` is the most recent version of the Internet Protocol. It uses a 128-bit address, allowing for a vastly larger number of unique addresses to accommodate the growth of the internet.

</details>
<details>
<summary>What is localhost?</summary><br>

In computer networking, `localhost` is a hostname that refers to the current device used to access it. It is used to access the network services that are running on the host via the loopback network interface. Using the loopback interface bypasses any local network interface hardware, and is typically used for testing and development purposes.
</details>
<details>
<summary>What is a subnet?</summary><br>

A `subnet`, or `subnetwork`, is a logical subdivision of an IP network. The practice of dividing a network into two or more networks is called subnetting. Subnetting can help reduce network traffic and hide network complexity. It is also a way of organizing the hosts into logical groups that mirrors an organization’s functional and security requirements.
</details>
<details>
<summary>Why was IPv6 created?</summary><br>

`IPv6` was primarily created to deal with the long-anticipated problem of IPv4 address exhaustion. As the Internet grew rapidly, it became clear that the 4.3 billion IP addresses provided by IPv4 weren't sufficient. `IPv6`, with its 128-bit address space, provides a vastly larger number of addresses, solving the problem of address exhaustion and supporting the continued expansion of the internet.
</details>

-----------------------

### TCP/UDP

<details>
<summary>What are TCP and UDP?</summary><br>

`TCP (Transmission Control Protocol)` and `UDP (User Datagram Protocol)` are two of the most common transport layer protocols. They are used to send data packets over the internet.
  
- `TCP` is connection-oriented, which means it requires a connection to be established before transferring data. It provides reliability by confirming packet delivery.
  
- `UDP` is connectionless, meaning it doesn't establish a connection and doesn't guarantee the delivery of data. It's often used for real-time services where speed is important and loss of data is acceptable.

</details>
<details>
<summary>What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)?</summary><br>

The two main protocols used for data transfer at the transport layer of the OSI Model are `TCP (Transmission Control Protocol)` and `UDP (User Datagram Protocol)`.
</details>
<details>
<summary>What is the main difference between TCP and UDP?</summary><br>

- `TCP (Transmission Control Protocol)` is connection-oriented, meaning it requires a connection to be established before transferring data. TCP provides reliability by confirming packet delivery, sequencing packets to preserve order, and error-checking to ensure data integrity. It's often used where reliability is critical, such as in file transfers, web browsing, and emails.
  
- `UDP (User Datagram Protocol)`, on the other hand, is connectionless, meaning it doesn't require a connection and doesn't guarantee delivery or order of data packets. This makes UDP faster and more efficient for many lightweight or real-time applications, such as live video streaming, where some data loss is acceptable.
</details>
<details>
<summary>What is a port?</summary><br>

In networking, a `port` is a virtual point where network connections start and end. `Ports` are identified by a number, and they establish specific paths for different types of data, allowing your computer to engage in multiple network tasks at the same time. Each `port` number corresponds to a specific protocol or service.
</details>
<details>
<summary>Memorize SSH, HTTP and HTTPS port numbers?</summary><br>

- `SSH (Secure Shell)` typically uses **port 22**. 
- `HTTP (Hyper Text Transfer Protocol)` typically uses **port 80**.
- `HTTPS (Hyper Text Transfer Protocol Secure)` typically uses **port 443**.
</details>
<details>
<summary>What tool/protocol is often used to check if a device is connected to a network?</summary><br>

The `tool/protocol` often used to check if a device is connected to a network is called Ping. Ping operates by sending Internet Control Message Protocol (ICMP) Echo Request messages to the destination host and waits for a response. If the device is connected, it responds back, confirming its connectivity.
</details>

----------------------

## Author

- Mathieu Morel
