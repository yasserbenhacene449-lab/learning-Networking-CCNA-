# learning-Networking-CCNA-
Daily hands-on lab documentation for Linux System Administration, Cloud Security, and Cisco CCNA networking fundamentals, tailored for corporate IT environments.
---

## 🌐 Week 1: Networking & CCNA Core (Jeremy's IT Lab)

### 🎥 Day 1: Network Devices (CCNA 200-301)
*   **Concepts Learned:** Understanding the foundational roles of network nodes and how enterprise infrastructures are built to share resources securely.
*   **Core Components Mastered:**
    *   **Clients & Servers:** Understood the client-server relationship where clients request services (like web browsers or smartphones) and servers fulfill them (like dedicated hardware or applications providing data).
    *   **Switches:** Mastered the role of Enterprise-grade Switches (e.g., Cisco Catalyst) which provide high-density port connectivity (typically 24+ ports) to aggregate and forward traffic locally within the same **LAN (Local Area Network)**.
    *   **Routers:** Learned that routers (e.g., Cisco ISR) have fewer interfaces than switches and are strictly designed to provide connectivity *between* different networks, enabling data forwarding across the Internet.
    *   **Firewalls:** Explored dedicated network security devices that control traffic entering and exiting the network based on security rules. Differentiated between hardware-based **Network Firewalls** and software-based **Host-based Firewalls**.
    *   **Next-Generation Firewalls (NGFW):** Understood how modern appliances (like Cisco Firepower or modern ASAs) upgrade traditional filtering by adding advanced features like **IPS (Intrusion Prevention Systems)**.

### 📝 Day 1 Quiz Results: Skills Assessment
*   **Status:** Successfully Passed ✅
*   **Key Validated Skills:**
    *   Correctly identified the **Switch** as the appropriate device for high-density local endpoint connectivity (e.g., connecting 30 departmental PCs).
    *   Validated the functional difference between an end-host acting as a server vs. a client in peer-to-peer (P2P) transactions (e.g., AirDrop).
 
    *   
    *   Demonstrated understanding of a **Router's** primary core competency in interconnecting separate networks over a Firewall or Switch.
    *   Distinguished **Next-Generation Firewalls (NGFW)** from traditional and host-based firewalls by identifying their advanced threat filtering capabilities.

<img width="1920" height="1080" alt="Screenshot 2026-06-21 211224" src="https://github.com/user-attachments/assets/32fb9f0f-89a4-447e-bf74-20c84f52ed19" />

---
---

### 🌐 Day 2: Network Interfaces, Cabling Standards & Practical Topology
*   **Concepts Learned:** Deep dive into Physical Layer components, Ethernet cabling standards (UTP vs. Fiber), and understanding interface pinouts crucial for production environments.
*   **Core Knowledge Mastered:**
    *   **Copper (UTP) vs. Fiber Optic:** Understood that UTP cables are legally limited to a maximum length of **100 meters** and are susceptible to Electromagnetic Interference (EMI).
    *   **Fiber Varieties (SMF vs. MMF):** Mastered the core differences between Single-mode Fiber (narrow core, laser-driven, long distances up to kilometers) and Multi-mode Fiber (wider core, LED-driven, cost-effective for shorter building-to-building distances).
    *   **Pinouts & Auto MDI-X:** Learned that End-hosts, Routers, and Firewalls transmit on pins 1,2 and receive on 3,6, while Switches do the exact opposite. Modern networks leverage **Auto MDI-X** to automatically negotiate these connections.
*   **Practical Lab Application (Cisco Packet Tracer):** 
    *   Successfully simulated a multi-device enterprise network architecture consisting of PCs, Switches, Routers, and Firewalls.
    *   Resolved physical hardware constraints in the lab by understanding device interface exhaustion and properly mapping physical cable connections between Firewalls and Core Routers.

> [!NOTE]
> Physical interfaces on enterprise devices (Routers and Firewalls) are shut down by default for security, requiring active administration (`no shutdown` command) to bring the links up.
> <img width="1930" height="1167" alt="Screenshot 2026-06-22 172345" src="https://github.com/user-attachments/assets/e7a248ad-5ce7-47ae-b18d-b3c48c26f95e" />
<img width="1920" height="1080" alt="Screenshot 2026-06-22 172310" src="https://github.com/user-attachments/assets/65bdef0f-9e17-40be-a978-4292241f74e4" />
<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/c51b6a23-8083-4ffb-a69d-d7490b1d1616" />

