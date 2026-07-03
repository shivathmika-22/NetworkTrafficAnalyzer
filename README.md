# Network Traffic Analyzer

A Java-based network packet analyzer built using Pcap4J and Maven. It captures live network packets from a selected network interface and displays packet data in real time.

## Features
- Capture live network packets
- List available network interfaces
- Display packet data in hexadecimal
- Built using Java and Maven
- Uses Pcap4J for packet capturing

## Technologies Used
- Java 17
- Maven
- Pcap4J
- WinPcap/Npcap

## How to Run

```bash
mvn clean install
mvn exec:java -Dexec.mainClass="com.alok.trafficanalyzer.PacketCapture"
```

## Future Improvements
- Decode TCP/UDP/ICMP packets
- Display Source/Destination IP addresses
- Display Port Numbers
- Export captured packets to CSV
- Add packet filtering
