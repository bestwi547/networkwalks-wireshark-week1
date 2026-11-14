Week 1 - Wireshark Labs 1 to 6 - NetworkWalks

What I Did
I used Wireshark to capture and analyse network traffic. I followed packets moving between devices and checked for normal and suspicious traffic.

Lab 1 - Introduction to Wireshark
1. I opened Wireshark and selected my active network interface.
2. I started a live capture and browsed the internet to generate traffic.
3. I stopped the capture and saved the file.
4. I learned the Wireshark interface - Packet List, Packet Details, and Packet Bytes.

Lab 2 - Capturing and Filtering Traffic
1. I used Display Filters to reduce noise, e.g. ip.addr == 192.168.1.1
2. I used Capture Filters to capture only the traffic I needed.
3. I learned the difference between Display Filter and Capture Filter.

Lab 3 - TCP / Three-Way Handshake
1. I filtered for TCP traffic: tcp
2. I followed a TCP Stream to see the full conversation.
3. I identified SYN, SYN-ACK, ACK - the Three-Way Handshake.
4. I learned how a connection is established and closed with FIN.

Lab 4 - DNS Analysis
1. I filtered for DNS: dns
2. I checked DNS Query and DNS Response packets.
3. I saw how a domain name is resolved to an IP address.
4. I checked for suspicious DNS queries.

 Lab 5 - HTTP Analysis
1. I filtered for HTTP: http
2. I followed an HTTP Stream to see GET Request and Response.
3. I checked for cleartext data, URLs, and user-agents in HTTP traffic.
4. I learned why HTTPS is safer than HTTP.

Lab 6 - Finding Suspicious Traffic
1. I looked for unusual traffic - many failed connections, large packets, strange protocols.
2. I used Statistics > Protocol Hierarchy to see which protocols were most used.
3. I used ip.src and ip.dst to find which devices were talking.
4. I learned how to spot normal vs suspicious traffic.

 Week 1 Summary
Wireshark showed me how real network traffic looks. I learned to capture, filter, follow TCP, DNS, and HTTP, and to identify suspicious activity. This is the foundation for network security and footprinting.
