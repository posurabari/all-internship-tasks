
# Task 5 – Wireshark Packet Capture and Analysis

## Objective
To capture and analyze live network traffic using Wireshark in Kali Linux, focusing on DNS and TCP communication.

## Tools Used
- **Wireshark** – For capturing and analyzing packets.
- **Web Browser** – For generating DNS and HTTP/HTTPS traffic.
- **Ping Command** – For generating ICMP requests.

## Steps Performed
1. **Open Wireshark** in Kali Linux.
2. **Select the active network interface** (e.g., eth0 or wlan0).
3. Click on the **Start Capturing Packets** button.
4. Generate traffic:
   - Open a browser and visit websites.
   - Or run `ping hackthissite` in the terminal.
5. Apply filters in the Wireshark filter bar:
   - `dns` → Show only DNS packets.
   - `tcp` → Show only TCP packets.
6. Stop the capture after collecting enough packets.
7. Analyze the captured packets and note important details like:
   - Source and destination IP addresses.
   - Protocol details.
   - Packet length and info.
8. Save the captured file for documentation.

## Output
The analysis revealed:
- DNS packets showing domain name resolutions.
- TCP packets showing connection establishment and data transfer.

## Conclusion
Wireshark is a powerful tool for network traffic analysis and troubleshooting, allowing visibility into DNS resolutions, TCP handshakes, and other protocol communications.
