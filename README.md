## Projects
![image](https://github.com/user-attachments/assets/457b75ba-39bf-4910-aeb3-5911d5c4daf0)

### Reliable File Transfer using Go-Back-N Protocol

**Brief Description:**  
Developed a reliable file transfer system using the Go-Back-N (GBN) protocol, focusing on ensuring data integrity and order over an unreliable network environment.

**Time Period:**  
March 2024 - April 2024

**Tools:**  
Python, Socket Programming, CRC-CCITT, Multi-threading, ConfigParser, CSV

**Key Achievements:**
- Implemented the Go-Back-N protocol to manage data transmission between two hosts, ensuring reliability through the use of sequence numbers and acknowledgments for transmitted frames.
- Designed the Protocol Data Unit (PDU) structure incorporating sequence numbers, acknowledgment numbers, control flags, payload data, and CRC checksums for error detection and data integrity.
- Enabled full-duplex communication using multi-threading, allowing simultaneous sending and receiving of files between hosts, mirroring real-world bidirectional communication scenarios.
- Configured dynamic parameters, including window size and timeout values, via INI files, providing flexibility to simulate different network conditions and assess the protocol's performance under various scenarios.
- Conducted extensive testing with error simulation, generating detailed log files for analysis, which included performance metrics such as transmission efficiency, error rates, and retransmissions.
