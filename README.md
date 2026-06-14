# Simple Network Sniffer

A lightweight, Python-based network packet sniffer utilizing the `scapy` library. This tool captures IP traffic and categorizes it by protocol (TCP/UDP), displaying real-time source and destination addresses along with their respective ports.

## Features
* Real-time packet capture and analysis.
* Differentiates between TCP, UDP, and other IP-layer protocols.
* Memory efficient (captured packets are not stored in RAM).

## Prerequisites
* Python 3.x
* Root/Administrator privileges (required for raw socket access).

## Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/korushhh/network-sniffer.git](https://github.com/korushhh/network-sniffer.git)
   cd network-sniffer
