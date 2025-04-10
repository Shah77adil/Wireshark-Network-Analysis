# 📊 Detailed Network Packet Analysis Report

This report includes an explanation of various packet captures analyzed during the OSS course project using **Wireshark**.

---

### 🟡 1. General View of Packets
**Screenshot:** `general_packet_view.png`  
This view displays all captured packets including different protocols like TCP, DNS, UDP, and ICMP. This is the default view when Wireshark captures traffic from a selected interface.

---

### 🟢 2. TCP Protocol Filter
**Screenshot:** `tcp_protocol_filter.png`  
**Filter Used:** `tcp`  
This filter shows only TCP-based packets, hiding other traffic like UDP and ARP. TCP is used for connection-oriented communication, ensuring reliable delivery.

---

### 🔵 3. DNS Protocol Filter
**Screenshot:** `dns_protocol_filter.png`  
**Filter Used:** `dns`  
This view isolates only DNS (Domain Name System) traffic. DNS is responsible for converting domain names (like google.com) into IP addresses.

---

### 🔴 4. RST Packet Analysis
**Screenshot:** `rst_packet_analysis.png`  
**Filter Used:** `tcp.flags.reset == 1`  
This shows only those packets where the TCP RST flag is set. RST (reset) flags are used to abruptly close a connection, indicating a failed connection attempt or rejection.

---

📌 **Conclusion:**  
Wireshark is a powerful tool to study real-time packet transmission and protocol behavior. These filtered views help us understand how data travels through networks and how connections behave under different protocols.