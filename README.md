# Packet-Sniffer
Python packet sniffer tool for educational purposes
Packet Sniffer

This Python tool captures and analyzes network packets. It displays information such as source and destination IP addresses, protocols, source and destination ports, and payload data.

## Features
- Captures live network packets using `scapy`.
- Displays IP addresses, protocols, and ports.
- Shows raw payload data when available.

## Usage

1. Clone the repository:
git clone https://github.com/your-username/Packet-Sniffer.git

2. Navigate to the project directory:
cd Packet-Sniffer

3. Install required dependencies:
pip install scapy

4. Run the packet sniffer:
sudo python packet_sniffer.py

Note: Running as `sudo` may be required to capture packets on certain systems.

5. The sniffer will start capturing packets and displaying information. Press `CTRL+C` to stop.

## Ethical Considerations

- Permission: Obtain explicit permission to capture network traffic.
- Use Cases: Use for educational purposes, network troubleshooting, or authorized security assessments.
- Compliance: Follow legal and organizational guidelines for network monitoring.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
