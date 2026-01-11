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

| OSI Layer | What it does | PDU Name | What it contains |
| :--- | :--- | :--- | :--- |
| **7. Application** | Provides network services to applications | Data | Message / User Data |
| **6. Presentation** | Translates, encrypts, and compresses data | Data | Translated / Formatted Data |
| **5. Session** | Manages and terminates connections | Data | Dialogue / Session Markers |
| **4. Transport** | Ensures reliable delivery and error recovery | Segment / Datagram | Port Numbers + Data |
| **3. Network** | Routes data through logical paths | Packet | IP Addresses + Data |
| **2. Data Link** | Provides physical addressing and error detection | Frame | MAC Addresses + Data |
| **1. Physical** | Transmits raw data over physical media | Bits | Electrical / Binary Pulses |
