# OSI vs TCP/IP Models

## OSI Model (7 Layers)

1. **Application Layer**  
   - End-user services (e.g., browsers, email clients).  
   - Protocols: HTTP, HTTPS, FTP, SMTP, DNS.  

2. **Presentation Layer**  
   - Translates data → Encryption, compression, encoding.  
   - Example: SSL/TLS encryption for HTTPS.  

3. **Session Layer**  
   - Manages sessions (open, maintain, close communication).  
   - Example: Keeping you logged in during a web session.  

4. **Transport Layer**  
   - Reliable delivery of data (segmentation, error checking).  
   - Protocols: TCP (reliable), UDP (fast, no reliability).  

5. **Network Layer**  
   - Logical addressing & routing.  
   - Protocols: IP (IPv4/IPv6), ICMP.  
   - Devices: Routers, Layer 3 switches.  

6. **Data Link Layer**  
   - Physical addressing using **MAC addresses**.  
   - Error detection/correction in frames.  
   - Protocols: Ethernet, PPP, Wi-Fi.  
   - Devices: Switches, NICs (Ethernet/Wi-Fi adapters).  

7. **Physical Layer**  
   - Transmission of raw bits over physical medium.  
   - Media: Cables, connectors, fiber optics, radio signals.  
   - Devices: Hubs, repeaters.  

---

## TCP/IP Model (4 Layers)

1. **Application Layer**  
   - Combines OSI’s Application + Presentation + Session layers.  
   - Protocols: HTTP, FTP, SMTP, DNS.  

2. **Transport Layer**  
   - End-to-end delivery, error checking.  
   - Protocols: TCP, UDP.  

3. **Internet Layer**  
   - Logical addressing & routing.  
   - Protocols: IP, ICMP, ARP.  

4. **Network Access Layer**  
   - Physical transmission + MAC addressing.  
   - Protocols: Ethernet, Wi-Fi.  

---

## OSI vs TCP/IP – Quick Mapping

| **OSI Layer**        | **TCP/IP Layer**      |
|-----------------------|-----------------------|
| Application           | Application           |
| Presentation          | Application           |
| Session               | Application           |
| Transport             | Transport             |
| Network               | Internet              |
| Data Link             | Network Access        |
| Physical              | Network Access        |

---

## 📌 Key Takeaways
- OSI → **theoretical model**, TCP/IP → **practical implementation**.  
- Protocols like **HTTP, DNS, TCP, IP, Ethernet** map directly into TCP/IP.  
- For hacking:  
  - Recon tools (Nmap, Wireshark) → focus on Transport & Network layers.  
  - Sniffing/spoofing attacks → Data Link & Network layers.  
  - Exploits/web hacking → Application layer.  
