# Computer Networks Labs

These lab exercises were conducted as part of the *Computer Networks* course. Each lab explores fundamental Internet protocols and networking mechanisms using **Wireshark** to observe real-world packet-level interactions, analyze protocol behaviors, and understand core network functionalities.

---

## Table of Contents
- [Lab 1 - Getting Started with Wireshark](#lab-1---getting-started-with-wireshark)
- [Lab 2 - HTTP Protocol](#lab-2---http-protocol)
- [Lab 3 - DNS Protocol](#lab-3---dns-protocol)
- [Lab 4 - IP Protocol](#lab-4---ip-protocol)
- [Lab 4b - NAT](#lab-4b---nat)
- [Lab 5 - DHCP](#lab-5---dhcp)
- [Lab 5b - ICMP Protocol](#lab-5b---icmp-protocol)
- [Lab 6 - Ethernet & ARP](#lab-6---ethernet--arp)
- [Lab 7 - 802.11 WiFi](#lab-7---80211-wifi)
- [Lab 7b - TLS](#lab-7b---tls)

---

## Lab 1 - Getting Started with Wireshark
**File:** [LAB01_Getting Started_Wireshark.pdf](https://github.com/phuongthanhkkk/Computer-Networks-Lab/blob/main/LAB01_Getting%20Started_Wireshark.pdf)
This introductory lab familiarizes students with the Wireshark tool, a network protocol analyzer used to capture and examine packets in real time.

**Topics Covered:**
- Packet sniffing concepts
- Wireshark interface navigation
- HTTP traffic analysis
- Filtering and interpreting captured packets
- Protocol stack and encapsulation understanding

---

## Lab 2 - HTTP Protocol
**File:** [LAB02_HTTP.pdf][(https://github.com/phuongthanhkkk/Computer-Networks-Lab/blob/main/LAB01_Getting%20Started_Wireshark.pdf)](https://github.com/phuongthanhkkk/Computer-Networks-Lab/blob/main/LAB02_HTTP.pdf)
This lab explores the Hypertext Transfer Protocol (HTTP), focusing on request/response interactions, message formats, and web object retrieval.

**Topics Covered:**
- HTTP GET/response basic interaction
- HTTP version identification
- Conditional GET and caching behavior
- Retrieval of long documents and TCP segmentation
- Embedded objects and parallel/serial downloading
- HTTP authentication and Base64 encoding
- Status codes and header analysis

---

## Lab 3 - DNS Protocol
**File:** `LAB03_DNS.docx`  
This lab investigates the Domain Name System (DNS), examining how hostnames are resolved to IP addresses and exploring DNS query/response messages.

**Topics Covered:**
- nslookup tool usage for DNS queries
- DNS record types (A, NS, MX)
- Authoritative vs. non-authoritative responses
- DNS message structure (queries and responses)
- UDP vs. TCP transport for DNS
- Local DNS server configuration
- DNS caching and TTL values
- Dynamic DNS concepts and providers

---

## Lab 4 - IP Protocol
**File:** `LAB04_IP.docx`  
This lab investigates the **IPv4 and IPv6** protocols by analyzing traceroute traffic, IP fragmentation, and the transition to IPv6.

**Topics Covered:**
- IP header structure and TTL behavior
- ICMP TTL-exceeded messages
- Fragmentation and reassembly in IPv4
- Identification field analysis
- IPv6 basics and packet differences

---

## Lab 4b - NAT
**File:** `LAB04_NAT.docx`  
This lab examines how **Network Address Translation (NAT)** works by analyzing packet transformations at both ends of a NAT router.

**Topics Covered:**
- NAT address translation
- TCP/UDP port rewriting
- HTTP GET and 200 OK message tracking
- IP header comparison before and after NAT
- NAT's effect on checksums and headers

---

## Lab 5 - DHCP
**File:** `LAB05_DHCP.docx`  
This lab explores the **Dynamic Host Configuration Protocol (DHCP)** and captures the full 4-step interaction (Discover, Offer, Request, ACK).

**Topics Covered:**
- DHCP message analysis
- UDP/IP encapsulation
- Transaction ID tracking
- Parameter Request Lists
- Client-server configuration exchanges

---

## Lab 5b - ICMP Protocol
**File:** `LAB05_ICMP.docx`  
This lab examines the Internet Control Message Protocol (ICMP), focusing on its role in network diagnostics through Ping and Traceroute utilities.

**Topics Covered:**
- ICMP echo request/reply (Ping)
- ICMP error messages (TTL exceeded)
- Traceroute implementation differences (Windows vs Unix)
- IP protocol number for ICMP
- ICMP message formats and fields
- Round-trip time (RTT) measurement
- Router path discovery and analysis
- Link delay identification in traceroute

---

## Lab 6 - Ethernet & ARP
**File:** `LAB06_ETHERNET&ARP.docx`  
This lab focuses on **Ethernet frame structure** and the **Address Resolution Protocol (ARP)**.

**Topics Covered:**
- Ethernet II frame format
- MAC address identification
- ARP request/reply structure
- ARP cache inspection and clearing
- Frame type and byte-level analysis

---

## Lab 7 - 802.11 WiFi
**File:** `LAB07_802.11 WiFi.docx`  
This lab investigates the **802.11 wireless LAN protocol**, including beacon frames, data transfer, and association/disassociation events.

**Topics Covered:**
- 802.11 MAC address roles
- SSID and channel analysis
- TCP over WiFi trace interpretation
- Wireless host/AP/router role distinction
- Beacon, probe, authentication, and association frames

---

## Lab 7b - TLS
**File:** `LAB07_TLS.docx`  
This lab examines the **Transport Layer Security (TLS)** protocol and its role in enabling secure HTTPS communication.

**Topics Covered:**
- TLS handshake: Client Hello & Server Hello
- Certificate verification and CA signatures
- Public key modulus and random bytes
- Change Cipher Spec and encryption start
- End-to-end message confidentiality and integrity
