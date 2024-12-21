# Network Traffic Analysis

## Project Overview
This project demonstrates the capture and analysis of network traffic in a controlled environment using Wireshark. It showcases the process of understanding packet flows, analyzing protocols, and detecting potential anomalies in network traffic.

## Tools Used
- **Wireshark**: Packet analysis tool.
- **Kali Linux**: Operating system for network monitoring and analysis.
- **Ubuntu**: Simulated host for generating network traffic.
- **VirtualBox**: Virtualization software for creating isolated network environments.

## Steps Taken
1. **Set Up Virtual Environment**:
   - Configured two VMs (Kali Linux and Ubuntu) in VirtualBox.
   - Assigned IP addresses to the Host-only Adapter for communication.

2. **Generated Network Traffic**:
   - Used `ping` to send ICMP packets between VMs.
   - Conducted a network scan with `nmap` from Kali Linux.

3. **Captured and Analyzed Traffic**:
   - Opened Wireshark on Kali Linux.
   - Captured packets on the Host-only Adapter.
   - Filtered traffic to view ICMP and ARP packets.

4. **Saved Findings**:
   - Saved the captured packets as `network_capture.pcap`.
   - Documented the observations.

## Key Observations
- **ICMP Traffic**:
  - Successfully captured `ping` requests and replies between the VMs.
  - Verified packet details such as source and destination IPs.

- **Network Scan**:
  - Detected ARP packets during the network scan performed by `nmap`.

- **Traffic Analysis**:
  - Observed the flow of packets and identified the protocols used in communication.

## How to Replicate
1. Set up a VirtualBox environment with two VMs (Kali Linux and Ubuntu).
2. Configure the network with NAT and Host-only Adapters.
3. Follow the steps outlined in this project to generate and capture network traffic.
4. Use Wireshark to analyze and filter packets.

## Screenshots
Include screenshots of:
- Wireshark capturing ICMP traffic.
- Filtered packet details.

## Capture File
The captured packets are saved in `network_capture.pcap` for further analysis.

## Conclusion
This project highlights the importance of understanding network traffic and using tools like Wireshark for effective packet analysis.
