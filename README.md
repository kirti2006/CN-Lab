# ENCS352 – Computer Networks lab

---

## 👨‍🎓 Submitted By

- **Name:** Kirti  
- **Roll No.:** 2301010165  
- **Programme:** B.Tech Computer Science & Engineering  
- **Section:** C  
- **Date:** 05 May 2026  

---

## Lab Assignments

---

### **Experiment - 1: Network Topologies**

Design and simulate bus, star, ring, mesh, and hybrid topologies.

#### **BUS TOPOLOGY**

Steps:
1. Open Cisco Packet Tracer  
2. Drag 4–5 PCs  
3. Add 1 Hub  
4. Connect all PCs to hub using straight-through cable  
5. Assign IPs (192.168.1.x)  
6. Send PDU  
7. Observe shared communication  

#### **STAR TOPOLOGY**

Steps:
1. Add 1 Switch  
2. Add PCs  
3. Connect each PC to switch  
4. Assign IPs  
5. Send PDU  
6. Observe centralized communication  

#### **RING TOPOLOGY**

Steps:
1. Add 4 PCs  
2. Connect PC1→PC2→PC3→PC4→PC1  
3. Use cross cables  
4. Assign IPs  
5. Send PDU  
6. Observe circular data flow  

#### **MESH TOPOLOGY**

Steps:
1. Add 4 PCs  
2. Connect each PC to every other PC  
3. Assign IPs  
4. Send PDU  
5. Observe multiple paths  

#### **HYBRID TOPOLOGY**

Steps:
1. Add switches + hub  
2. Connect star + bus  
3. Assign IPs  
4. Send PDU  
5. Observe combined behavior  

---

### **Experiment - 2: Packet & Circuit Switching**

#### **Circuit Switching**

Steps:
1. Create network with routers  
2. Assign IP addresses  
3. Configure router interfaces  
4. Enable using `no shutdown`  
5. Configure static routing  
6. Send ping  
7. Observe fixed path  
8. Note dedicated channel  

#### **Packet Switching**

Steps:
1. Create network using switch  
2. Connect PCs  
3. Assign IPs  
4. Use simulation mode  
5. Send PDU  
6. Observe packet movement  
7. Verify delivery  

---

### **Experiment - 3: Packet Delay, Loss & Throughput**

Steps:
1. Create network with PCs and switch  
2. Assign IP addresses  
3. Verify connectivity using ping  
4. Start continuous ping  
5. Disconnect cable  
6. Observe packet loss  
7. Reconnect cable  
8. Observe recovery  
9. Analyze delay  
10. Record results  

---

### **Experiment - 4: Error Detection & Correction (CRC & Block Coding)**

Steps:
1. Create network with 2 PCs and switch  
2. Assign IP addresses  
3. Send data using PDU  
4. Add note explaining block coding  
5. Simulate parity bits  
6. Introduce error (disconnect link)  
7. Observe error detection  
8. Explain CRC mechanism  
9. Verify retransmission  
10. Analyze results  

---

### **Experiment - 5: Flow Control Protocols**

Steps:
1. Create sender and receiver network  
2. Assign IP addresses  
3. Simulate Stop & Wait protocol  
4. Observe ACK after each frame  
5. Simulate Go-Back-N ARQ  
6. Send multiple frames  
7. Introduce error  
8. Observe retransmission  
9. Simulate Selective Repeat ARQ  
10. Compare performance  

---

### **Experiment - 6: Multiple Access Protocols**

#### **CSMA/CD**

Steps:
1. Sense channel  
2. If idle → transmit  
3. If busy → wait  
4. Detect collision  
5. Send jam signal  
6. Stop transmission  
7. Wait backoff time  
8. Retransmit  

#### **CSMA/CA**

Steps:
1. Sense channel  
2. If idle → wait IFS  
3. Send RTS  
4. Receive CTS  
5. Transmit data  
6. Receive ACK  
7. If no ACK → retransmit  

---

### **Experiment - 7: Sliding Window Protocol**

Steps:
1. Create network with 2 PCs  
2. Assign IP addresses  
3. Send multiple frames  
4. Observe sliding window  
5. Track sequence numbers  
6. Implement piggybacking  
7. Observe ACK inside frames  
8. Use simulation mode  
9. Analyze performance  
10. Conclude efficiency  

---

### **Experiment - 8: Logical Addressing (IPv4, IPv6, ARP, DHCP, BOOTP, RARP)**

Steps:
1. Create network with PCs and server  
2. Assign IPv4 and IPv6 addresses  
3. Simulate ARP (IP → MAC)  
4. Observe ARP request/reply  
5. Enable DHCP on server  
6. Configure DHCP pool  
7. Assign automatic IPs  
8. Simulate BOOTP and RARP  
9. Test connectivity  
10. Analyze mapping  

---

### **Experiment - 9: Transport Layer (UDP, TCP, SCTP)**

Steps:
1. Create network  
2. Assign IP addresses  
3. Simulate UDP communication  
4. Simulate TCP communication  
5. Simulate SCTP  
6. Observe connection setup  
7. Compare reliability  
8. Analyze congestion control  
9. Test using ping  
10. Record observations  

---

### **Experiment - 10: DNS & DDNS**

Steps:
1. Create DNS server and PCs  
2. Assign IP addresses  
3. Enable DNS service  
4. Add domain records  
5. Configure DNS on client  
6. Query using browser  
7. Observe resolution  
8. Update DNS record  
9. Verify changes  
10. Analyze dynamic update  

---

### **Experiment - 11: HTTP & Web Server**

Steps:
1. Create network with server and PCs  
2. Assign IP addresses  
3. Enable HTTP service  
4. Create HTML webpage  
5. Open browser on PC  
6. Enter server IP  
7. Load webpage  
8. Use simulation mode  
9. Observe HTTP GET request  
10. Analyze response  

---

## ✅ Conclusion

All experiments were successfully implemented using Cisco Packet Tracer.  
Various networking concepts including switching, routing, protocols, and simulations were studied and analyzed effectively.

---
