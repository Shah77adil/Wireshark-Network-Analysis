# Wireshark-Based Network Analysis Project

This project is part of our OSS (Open Source Software) course, where we analyze different network protocols using **Wireshark**, a powerful packet sniffing and network analysis tool.

## 🔍 Objective
To observe and analyze real-time network traffic using Wireshark, and apply protocol filters (TCP, DNS, RST, etc.) to capture and understand network behavior.

## 🛠️ Tools Used
- **Wireshark**
- **TCP/IP Stack**
- **DNS Protocol**
- **RST Flag Analysis**

## 📂 Screenshots Included
| Screenshot | Description |
|------------|-------------|
| `dns_protocol_filter.png` | Capturing DNS packets only using filter `dns` |
| `general_packet_view.png` | Overview of all captured packets |
| `rst_packet_analysis.png` | Filtering RST packets using `tcp.flags.reset == 1` |
| `tcp_protocol_filter.png` | Showing only TCP traffic using filter `tcp` |

## 📚 How to Use Wireshark Filters
- `tcp` → Show only TCP packets
- `dns` → Show only DNS queries/responses
- `tcp.flags.reset == 1` → Show only RST (reset) flagged packets

## 🙋‍♂️ Author
Shaheer Adil — 7th Semester CS  
GitHub: [YourGitHubProfile]

## 📜 License
This project is for educational purposes only.