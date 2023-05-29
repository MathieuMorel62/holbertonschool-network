# <p align="center">Networking Basics #0</p>
<img src="https://wallpaperaccess.com/full/2221204.jpg" width="100%">

## Resources
### Read or Watch:

- [OSI Model](https://en.wikipedia.org/wiki/OSI_model)
- [Different Types Of Network](https://www.lifewire.com/lans-wans-and-other-area-networks-817376)
- [LAN Network](https://en.wikipedia.org/wiki/Local_area_network)
- [WAN Network](https://en.wikipedia.org/wiki/Wide_area_network)
- [Internet]https://en.wikipedia.org/wiki/Internet)
- [MAC Address](https://whatismyipaddress.com/mac-address)
- [What Is An IP Address](https://www.bleepingcomputer.com/tutorials/ip-addresses-explained/)
- [Private And Public Address](https://www.iplocation.net/public-vs-private-ip-address)
- [IPv4 And IPv6](https://www.webopedia.com/insights/ipv6-ipv4-difference/)
- [Localhost](https://en.wikipedia.org/wiki/Localhost)
- [TCP And UDP](https://www.howtogeek.com/190014/htg-explains-what-is-the-difference-between-tcp-and-udp/)
- [TCP/UDP Ports List](https://en.wikipedia.org/wiki/List_of_TCP_and_UDP_port_numbers)
- [What Is Ping /ICMP](https://en.wikipedia.org/wiki/Ping_%28networking_utility%29)

## Requirements

- Allowed editors: `vi`, `vim`, `emacs`
- All your Bash script files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A `README.md` file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass `shellcheck` without any error
- The first line of all your Bash scripts should be exactly `#!/usr/bin/env bash`
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## More Info

The second line of all your Bash scripts should be a comment explaining what is the script doing
  
For multiple choice question type tasks, just type the number of the correct answer in your answer file, add a new line for every new answer, example:

```bash
What is the most important position in a software company?

1. Project manager
2. Backend developer
3. System administrator


mathieu@ubuntu$ cat foo_answer_file
3
```

Source for question 1 [here](https://twitter.com/devopsreact/status/831922429215662080)

----------------------------

# TASKS

### [0. OSI Model](https://github.com/MathieuMorel62/holbertonschool-network/blob/main/basics_0/0-OSI_model)
OSI (Open Systems Interconnection) is an abstract model to describe layered communication and computer network design. The idea is to segregate the different parts of what make communication possible.
  
It is organized from the lowest level to the highest level:
  
- The lowest level: layer 1 which is for transmission on physical layers with electrical impulse, light or radio signal
- The highest level: layer 7 which is for application specific communication like SNMP for emails, HTTP for your web browser, etc
  
Keep in mind that the OSI model is a concept, it’s not even tangible. The OSI model doesn’t perform any functions in the networking process. It is a conceptual framework so we can better understand complex interactions that are happening. Most of the functionality in the OSI model exists in all communications systems.

<img src="https://github.com/MathieuMorel62/holbertonschool-network/assets/113856302/60d9c710-91c2-4999-b1a2-88a1d4c9d977">

In this project we will mainly focus on:
  
- The Transport layer and especially TCP/UDP
- On the Network layer with IP and ICMP
  
The image bellow describes more concretely how you can relate to every level.

<img src="https://github.com/MathieuMorel62/holbertonschool-network/assets/113856302/f9d835e1-9aa1-42bc-b88d-f5d10d521466">

**Questions:**

<details>
<summary>What is the OSI model?</summary><br>
  
1. Set of specifications that network hardware manufacturers must respect
  
2. The OSI model is a conceptual model that characterizes the communication functions of a telecommunication system without regard to their underlying internal structure and technology
  
3. The OSI model is a model that characterizes the communication functions of a telecommunication system with a strong regard for their underlying internal structure and technology
</details>
<br>
<details>
<summary>How is the OSI model organized?</summary><br>

1. Alphabetically
  
2. From the lowest to the highest level
  
3. Randomly
</details>

--------------------

### [1. Types Of Network](https://github.com/MathieuMorel62/holbertonschool-network/blob/main/basics_0/1-types_of_network)

<img src="https://github.com/MathieuMorel62/holbertonschool-network/assets/113856302/62d4d427-6755-4230-9dfd-0ec3fbbe4c29">

LAN connect local devices together, WAN connects LANs together, and WANs are operating over the Internet.

**Questions:**

<details>
<summary>What type of network a computer in local is connected to?</summary><br>

1. Internet
  
2. WAN
  
3. LAN
</details>
<br>
<details>
<summary>What type of network could connect an office in one building to another office in a building a few streets away?</summary><br>

1. Internet
  
2. WAN
  
3. LAN
</details>
<br>
<details>
<summary>What network do you use when you browse www.google.com from your smartphone (not connected to the Wifi)?</summary><br>

1. Internet
  
2. WAN
  
3. LAN
</details>

--------------------

### [2. MAC And IP Address](https://github.com/MathieuMorel62/holbertonschool-network/blob/main/basics_0/2-MAC_and_IP_address)

<img src="https://github.com/MathieuMorel62/holbertonschool-network/assets/113856302/d2efd03e-963c-4e16-bb81-e6a8edfa5488">

**Questions:**

<details>
<summary>What is a MAC address?</summary><br>

1. The name of a network interface
  
2. The unique identifier of a network interface
  
3. A network interface
</details>
<br>
<details>
<summary>What is an IP address?</summary><br>

1. Is to devices connected to a network what postal address is to houses
  
2. The unique identifier of a network interface
  
3. Is a number that network devices use to connect to networks
</details>

--------------------------

### [3. UDP And TCP](https://github.com/MathieuMorel62/holbertonschool-network/blob/main/basics_0/3-UDP_and_TCP)

<img src="https://github.com/MathieuMorel62/holbertonschool-network/assets/113856302/2e9c2417-a488-40ef-bcd3-08a025f270fd">

Let’s fill the empty parts in the drawing above.
  
** Questions**

<details>
<summary>Which statement is correct for the TCP box:</summary><br>

1. It is a protocol that is transferring data in a slow way but surely
  
2. It is a protocol that is transferring data in a fast way and might loss data along in the process
</details>
<br>
<details>
<summary>Which statement is correct for the UDP box:</summary><br>

1. It is a protocol that is transferring data in a slow way but surely
  
2. It is a protocol that is transferring data in a fast way and might loss data along in the process
</details>
<br>
<details>
<summary>Which statement is correct for the TCP worker:</summary><br>

1. Have you received boxes x, y, z?
  
2. May I increase the rate at which I am sending you boxes?
</details>

------------------

### [4. TCP And UDP Ports](https://github.com/MathieuMorel62/holbertonschool-network/blob/main/basics_0/4-TCP_and_UDP_ports)

Once packets have been sent to the right network device using IP using either UDP or TCP as a mode of transportation, it needs to actually enter the network device.
  
If we continue the comparison of a network device to your house, where IP address is like your postal address, UDP and TCP ports are like the windows and doors of your place. A TCP/UDP network device has 65535 ports. Some of them are officially reserved for a specific usage, some of them are known to be used for a specific usage (but nothing is officially declared) and the rest are free of use.
  
While the full list of ports should not be memorized, it is important to know the most used ports, let’s start by remembering 3 of them:
  
- **22** for SSH
- **80** for HTTP
- **443** for HTTPS
  
Note that a specific [IP + port = socket](https://stackoverflow.com/questions/152457/what-is-the-difference-between-a-port-and-a-socket).
  
Write a Bash script that displays listening ports:
  
- That only shows listening sockets
- That shows the PID and name of the program to which each socket belongs
  
**Example:**

<details>
<summary>File Test</summary><br>

```bash
mathieu@ubuntu$ sudo ./4-TCP_and_UDP_ports
  
Active Internet connections (only servers)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name
tcp        0      0 *:sunrpc                *:*                     LISTEN      518/rpcbind
tcp        0      0 *:ssh                   *:*                     LISTEN      1240/sshd
tcp        0      0 *:32938                 *:*                     LISTEN      547/rpc.statd
tcp6       0      0 [::]:sunrpc             [::]:*                  LISTEN      518/rpcbind
tcp6       0      0 [::]:ssh                [::]:*                  LISTEN      1240/sshd
tcp6       0      0 [::]:33737              [::]:*                  LISTEN      547/rpc.statd
udp        0      0 *:sunrpc                *:*                                 518/rpcbind
udp        0      0 *:691                   *:*                                 518/rpcbind
udp        0      0 localhost:723           *:*                                 547/rpc.statd
udp        0      0 *:60129                 *:*                                 547/rpc.statd
udp        0      0 *:3845                  *:*                                 562/dhclient
udp        0      0 *:bootpc                *:*                                 562/dhclient
udp6       0      0 [::]:47444              [::]:*                              547/rpc.statd
udp6       0      0 [::]:sunrpc             [::]:*                              518/rpcbind
udp6       0      0 [::]:50038              [::]:*                              562/dhclient
udp6       0      0 [::]:691                [::]:*                              518/rpcbind
Active UNIX domain sockets (only servers)
Proto RefCnt Flags       Type       State         I-Node   PID/Program name    Path
unix  2      [ ACC ]     STREAM     LISTENING     7724     518/rpcbind         /run/rpcbind.sock
unix  2      [ ACC ]     STREAM     LISTENING     6525     1/init              @/com/ubuntu/upstart
unix  2      [ ACC ]     STREAM     LISTENING     8559     835/dbus-daemon     /var/run/dbus/system_bus_socket
unix  2      [ ACC ]     STREAM     LISTENING     9190     1087/acpid          /var/run/acpid.socket
unix  2      [ ACC ]     SEQPACKET  LISTENING     7156     378/systemd-udevd   /run/udev/control
```
</details>

------------------

### [5. Is The Host On The Network](https://github.com/MathieuMorel62/holbertonschool-network/blob/main/basics_0/5-is_the_host_on_the_network)

The Internet Control Message Protocol (ICMP) is a protocol in the Internet protocol suite. It is used by network devices, to check if other network devices are available on the network. The command ping uses ICMP to make sure that a network device remains online or to troubleshoot issues on the network.
  
Write a Bash script that pings an IP address passed as an argument.
  
Requirements:
  
- Accepts a string as an argument
- Displays `Usage: 5-is_the_host_on_the_network {IP_ADDRESS}` if no argument passed
- Ping the IP 5 times
  
**Example:**

<details>
<summary>File Test</summary><br>

```bash
mathieu@ubuntu$ ./5-is_the_host_on_the_network 8.8.8.8

PING 8.8.8.8 (8.8.8.8) 56(84) bytes of data.
64 bytes from 8.8.8.8: icmp_seq=1 ttl=63 time=12.9 ms
64 bytes from 8.8.8.8: icmp_seq=2 ttl=63 time=13.6 ms
64 bytes from 8.8.8.8: icmp_seq=3 ttl=63 time=7.83 ms
64 bytes from 8.8.8.8: icmp_seq=4 ttl=63 time=11.3 ms
64 bytes from 8.8.8.8: icmp_seq=5 ttl=63 time=7.57 ms

--- 8.8.8.8 ping statistics ---
5 packets transmitted, 5 received, 0% packet loss, time 4006ms
rtt min/avg/max/mdev = 7.570/10.682/13.679/2.546 ms


mathieu@ubuntu$ ./5-is_the_host_on_the_network
Usage: 5-is_the_host_on_the_network {IP_ADDRESS}
```
</details>

It is interesting to look at the `time` value, which is the time that it took for the ICMP request to go to the `8.8.8.8` IP and come back to my host. The IP `8.8.8.8` is owned by Google, and the quickest roundtrip between my computer and Google was 7.57 ms which is pretty fast, which is a sign that the network path between my computer and Google’s datacenter is in good shape. A slow ping would indicate a slow network.
  
Next time you feel that your connection is slow, try the `ping` command to see what is going on!

---------------------

## Author

- Mathieu Morel
