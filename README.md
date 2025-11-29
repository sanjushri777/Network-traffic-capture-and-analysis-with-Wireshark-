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

<img width="955" height="1020" alt="Screenshot 2025-10-10 083911" src="https://github.com/user-attachments/assets/5fe9a429-ed03-4309-9122-7521b4fdc43c" />
<img width="961" height="1018" alt="image" src="https://github.com/user-attachments/assets/61fa74e4-f40c-459f-9bac-61f10f138f3b" />
<img width="758" height="816" alt="image" src="https://github.com/user-attachments/assets/a87d51fd-5943-451c-a293-22023377a7c8" />



## ip
<img width="1012" height="1017" alt="image" src="https://github.com/user-attachments/assets/5efe4b3a-99f7-4c36-a416-0e723ecc12ed" />

## udp
<img width="959" height="1013" alt="Screenshot 2025-10-10 094729" src="https://github.com/user-attachments/assets/f9aa861c-f14c-401d-b831-81470b4e63d1" />

## tcp
<img width="1014" height="1018" alt="image" src="https://github.com/user-attachments/assets/9080a26b-6717-4071-a172-f2a6b8fb93da" />

## suspicious activity
<img width="1098" height="1015" alt="image" src="https://github.com/user-attachments/assets/3df53210-834b-4016-ae18-650bf216e120" />







 






## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
