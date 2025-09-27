**🛰️ Network Traffic Analyzer**

A lightweight Python-based tool to capture, analyze, and log network traffic in real time.
This project was built to practice network security concepts, protocol analysis, and traffic monitoring, inspired by tools like Wireshark.

**📌 Features**

Capture live network packets on a chosen interface.

Filter traffic by protocol (ICMP, TCP, UDP, DNS, etc.).

Extract key details (source IP, destination IP, protocol, packet size).

Export captured packets into CSV/JSON for further analysis.

Display real-time traffic stats on the terminal.

**🖼️ Demo – Wireshark Validation**

Before implementing the analyzer, I validated packet capture using Wireshark.
The screenshot below shows ICMP echo requests/replies being captured between a local machine and an external server:

This demonstrates successful detection of packet exchanges, which I later replicated with my Python analyzer.

**⚙️ How It Works**

The tool listens to a network interface (e.g., wlan0, eth0).

Captured packets are inspected for protocol type and IP details.

Data is printed live and optionally saved to a file.
