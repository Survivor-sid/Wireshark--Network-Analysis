# Wireshark Network Traffic Analysis

## What I Learned

Through this task, I gained practical experience in capturing and analyzing live network traffic using Wireshark. I learned how different network protocols communicate, how to apply protocol filters, and how to inspect packet-level information. This exercise also improved my understanding of the TCP/IP model and the role of packet analysis in network troubleshooting and cybersecurity investigations.

---

## Protocols Identified

During the packet capture and analysis process, the following protocols were identified:

### 1. DNS (Domain Name System)

* Used to translate domain names into IP addresses.
* Observed when accessing websites such as Google and GitHub.

### 2. TCP (Transmission Control Protocol)

* Provides reliable, connection-oriented communication.
* Used extensively during web browsing and HTTPS sessions.

### 3. ICMP (Internet Control Message Protocol)

* Used for network diagnostics and connectivity testing.
* Observed through ping requests and replies.

### 4. TLS/HTTPS

* Provides encrypted communication between clients and servers.
* Observed during secure web browsing activities.

---

## Challenges Faced

* Capturing a large volume of packets made analysis more complex.
* Distinguishing relevant traffic from background system traffic required the use of filters.
* Understanding packet details and protocol hierarchy initially required additional research.
* Encrypted HTTPS traffic limited visibility into the actual application data being transmitted.

---

## Key Takeaways

* Wireshark is a powerful tool for monitoring and analyzing network communications.
* DNS queries typically occur before establishing connections to websites.
* TCP is the primary protocol used for reliable internet communication.
* ICMP packets are useful for testing connectivity and diagnosing network issues.
* Most modern web traffic is protected using TLS encryption.
* Packet analysis plays an important role in network troubleshooting, performance monitoring, and cybersecurity investigations.
* Effective use of filters significantly improves packet analysis efficiency.

---

## Conclusion

This task provided valuable hands-on experience with network traffic analysis. By capturing and examining real network packets, I developed a stronger understanding of networking fundamentals, protocol behavior, and packet-level communication. The knowledge gained from this exercise forms a solid foundation for further studies in cybersecurity, network administration, and digital forensics.
