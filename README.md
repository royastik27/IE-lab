# IE-lab
Basics of Internet Engineering Lab.

## 1. Configure a LAN Using HUB and observe its behavior.
### Hubs
- Hubs work at the **physical layer** of the OSI model.
- Used to set up **LAN**.

### Notes
- **A Hub or A switch** can be used for the problem.
- When we connect computers with a hub, we make a **star topology**.

> **PDU (Protocol Data Unit):** In simple terms, a PDU is the **technical name** for a unit of data at any specific layer of the OSI model. While people often use the word "packet" for everything, "packet" is actually only the name for data at Layer 3.

| OSI Layer | PDU Name | What it contains |
| :--- | :--- | :--- |
| **7. Application** | **Data** | Network services (HTTP, FTP, SMTP) |
| **6. Presentation** | **Data** | Encryption, Compression, Formatting |
| **5. Session** | **Data** | Session management and Synchronization |
| **4. Transport** | **Segment / Datagram** | Data + Port numbers (TCP/UDP) |
| **3. Network** | **Packet** | Data + IP addresses |
| **2. Data Link** | **Frame** | Data + MAC addresses |
| **1. Physical** | **Bits** | Raw binary (0s and 1s) |
