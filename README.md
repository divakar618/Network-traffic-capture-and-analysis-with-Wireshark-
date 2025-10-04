# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1919" height="1079" alt="Screenshot 2025-10-04 121413" src="https://github.com/user-attachments/assets/aeec0136-2205-40ff-b32b-2527d0502417" />

<img width="1910" height="1079" alt="Screenshot 2025-10-04 124227" src="https://github.com/user-attachments/assets/50a6f2e8-2291-48f7-a925-6e943463605c" />

<img width="1528" height="814" alt="Screenshot 2025-10-04 124252" src="https://github.com/user-attachments/assets/c0e6ec30-97c6-46a2-ab34-ea8e3dc72bb5" />

<img width="1918" height="1079" alt="Screenshot 2025-10-04 124611" src="https://github.com/user-attachments/assets/f23f5104-f288-41bb-9478-52c50b51f647" />

<img width="1625" height="896" alt="Screenshot 2025-10-04 124655" src="https://github.com/user-attachments/assets/badbfc7c-b372-47b2-9c20-a89268ecc9af" />

<img width="1913" height="1075" alt="Screenshot 2025-10-04 124735" src="https://github.com/user-attachments/assets/10f1b851-0f20-473b-9225-c7c7a93780ea" />

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
