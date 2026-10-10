# Network Packet Sniffer

A simple and lightweight **Python network packet sniffer** built using **Scapy**.  
It captures live network traffic, identifies protocols, and displays real-time packet information along with useful statistics.

## Features

- Live packet capturing
- Protocol filtering (All, TCP, UDP, ICMP)
- Real-time packet details (Source, Destination, Protocol, Size)
- Total packets & bytes tracking
- Protocol-wise statistics
- Top Source & Destination IP tracking

## Requirements

- Python 3.x
- Scapy
- Administrator / Root privileges

### Installation

```bash
pip install scapy

# Linux / macOS
sudo python packet_sniffer.py

# Windows (Run as Administrator)
python packet_sniffer.py

1. All packets
2. TCP
3. UDP
4. ICMP

----------------------------------------------------------------------
Protocol     : TCP
Source       : 192.168.1.5:54321
Destination  : 142.250.190.78:443
Packet Size  : 66 bytes
----------------------------------------------------------------------
