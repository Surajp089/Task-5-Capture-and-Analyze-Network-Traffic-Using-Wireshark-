# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets using Wireshark, identify at least 3 protocols, and analyze basic network communication.

## Tools
- Wireshark
- Internet connection

## Steps Performed
1. Installed Wireshark with Npcap.
2. Selected active network interface.
3. Generated traffic by browsing and pinging servers.
4. Applied protocol filters (`dns`, `http`, `tcp`).
5. Identified DNS, TCP, and HTTP packets.
6. Exported capture as `.pcap`.

## Protocols Identified
| Protocol | Purpose |
|----------|---------|
| DNS      | Domain name resolution |
| TCP      | Reliable communication |
| HTTP     | Web page transfer |

## Files in Repo
- `network_capture.pcap` – Packet capture file.
- `Task 5.pdf` – Full report.
- Screenshots – Steps & analysis.

## Sample Screenshots
- File saved successfully.png
- Filtering DNS.png
- Filtering HTTP.png
- Filtering TCP.png
- Installation of Wireshark.png
- Pinging google.com.png
- Network traffic after pinging google.com.png
- Saving .pcap file.png
- Starting to Capture Packets.png
- Wireshark Dashboard.png
- Wireshark Installation Link.png

## Protocols Identified & Details

- DNS	>> Resolves domain names to IP addresses
- TCP	Reliable>>connection-oriented data transmission	SYN, SYN-ACK packets
- HTTP>> Transfers web pages between client & server	GET request to www.example.com

## Sample Findings
During packet capture:
- DNS packets were observed when accessing websites.
- TCP handshake (SYN → SYN-ACK → ACK) was captured.
- HTTP GET request showed browser requesting HTML content.
- HTTPS packets appeared but payload was encrypted.

## Summary
- Successfully captured live network packets.
- Identified DNS, TCP, HTTP protocols.
- Learned to apply filters and analyze traffic.
