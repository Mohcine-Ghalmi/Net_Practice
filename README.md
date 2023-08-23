# Net_Practice

<a src="https://cdn.intra.42.fr/pdf/pdf/93152/en.subject.pdf">subject</a>

<p align="center">
<img src="https://github.com/Mohcine-Ghalmi/Net_Practice/assets/81354228/436c7b35-b87e-4f20-9d49-8cd3be0edb48">
</p>

## What is an IP?

>An IP address, short for ``Internet Protocol Address``, represents a set of guidelines governing internet communication, including activities like sending emails, streaming videos, and accessing websites. Essentially, an IP address serves as a label for identifying either a network or a device on the internet.


<p align="center">
<img src="https://github.com/Mohcine-Ghalmi/Net_Practice/assets/81354228/3a508266-d17c-4cfc-a309-7f6c190f575e" alt="mghalmi 42" width="500">
</p>
 
><i>This label consists of two vital components:</i> </br>

1- <b>THE NETWORK ID </b> 

--> `identifies the host such as a computer or other device`</br>
2- <b>THE HOST ID</b> </br>
--> ``identifies the network it belongs to``

## What is the role of IP addresses?

> The primary role of an IP address is to facilitate connections between devices that exchange data throughout a network. Each device on the internet is distinctively marked by an IP address; without it, communication would be impossible. IP addresses enable computing devices to interact with destinations such as websites and streaming platforms, also revealing the identity of the connecting users to these websites.

## IP address come in two 2 versions
<h4>IPv4 :</h4>

>Introduced in 1981, operating with a 32-bit address format, and possessing just over 4.3 billion addresses (a relatively limited pool compared to IPv6), this version of IP necessitates the recycling and concealing of addresses. It employs the Numeric Dot-Decimal Notation `(e:, 192.108.42.64)` and mandates manual configuration.

<h4>IPv6 :</h4>

>Rolled out in 1998, functioning with a 128-bit address architecture, and encompassing a staggering quantity of over 340 undecillion addresses (equivalent to 340 trillion, trillion, trillion, trillion, or 36 zeros), this iteration of IP ensures that each device can possess its individualized IP address. It employs the Alphanumeric Hexadecimal Notation `(e:, 2002:0de6:0001:0042:0100:8c2e:0370:7234)` and seamlessly accommodates auto-configuration capabilities.

## What is TCP/IP

<b>TCP/IP uses a subnet mask to separate netwrok id and host id</b>

>TCP/IP stands for ransmission Control Protocol/Internet Protocol </br>
TCP/IP is a set of protocols that form the foundation of the internet and most modern computer networks. It's a suite of communication protocols that govern how data is transmitted, routed, and received across networks, including the internet.

## What is the difference between TCP and IP?

<B><ins>Transmission Control Protocol (TCP):</ins></B> TCP is responsible for breaking data into smaller packets for transmission over a network and ensuring that these packets are delivered reliably and in the correct order. It manages the establishment, maintenance, and termination of connections between devices.</br>

<B><ins>Internet Protocol (IP):</ins></B> IP is responsible for addressing and routing packets of data so that they can be sent from one device to another across different networks. It defines the structure of IP addresses, which are used to identify devices on a network, and it handles the routing of data through routers and switches.

## How does TCP/IP work?

>Together, TCP and IP provide a standardized framework for communication between devices over the internet. They allow data to be efficiently transmitted, routed, and received across various types of networks, enabling seamless communication between computers, servers, and other devices.

<h4>TCP/IP job is to divide the different communication tasks into layers</h4>

<p align="center">
<img src="https://github.com/Mohcine-Ghalmi/Net_Practice/assets/81354228/88804d16-6372-4afd-aa95-6e905fe2bba9" alt="mghalmi 42" width="500">
</p>

<B><ins>Application Layer:</ins></B> This top layer is where applications and services interact with the network. It handles user interfaces, email, web browsing, and other high-level functions. Protocols like HTTP (web), SMTP (email), and FTP (file transfer) operate here.

<B><ins>Transport Layer:</ins></B> The transport layer manages data delivery between devices. It's responsible for breaking data into packets, ensuring reliable transmission, and managing connections. `TCP` provides error checking and reliable data transfer, while `UDP: user datagram protoco` offers faster, connectionless transmission.

<B><ins>Internet Layer:</ins></B> This layer handles addressing, routing, and packet forwarding. It uses IP addresses to identify devices and route data packets between networks. The Internet Protocol (IP) is the core of this layer.

<B><ins>Link Layer:</B></ins> Also known as the Network Interface Layer, this layer deals with the physical connection between devices and the local network. It manages data frames, addresses, and access to the physical transmission medium, like Ethernet or Wi-Fi.

>the four layers of the TCP/IP model ensure that applications can communicate across networks by breaking down communication tasks into manageable components: application handling, data transport, routing, and physical connection management.
