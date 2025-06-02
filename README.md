# InternshipTask5
ElevateLabs Internship Task5
# 🚀 Wireshark Packet Capture Exercise  

Welcome to the Wireshark Packet Capture Exercise! This guide documents the steps taken during the process of capturing and analyzing network traffic using Wireshark. Each step includes a screenshot to illustrate the progress.  

--- 

## 📸 Steps  

### 🖥️ Step 1: Installation
- Install Wireshark from official Website
![Screenshot 2025-06-02 120924](https://github.com/user-attachments/assets/cd1f1c6f-167b-4e3d-bd7a-0bb1c66fed78)
![Screenshot 2025-06-02 120948](https://github.com/user-attachments/assets/566f23d9-2a7c-414d-9a3c-854f4c077c6d)

---

### 🖥️ Step 2: Launch Wireshark and Start Capture
- Open Wireshark and ensure it’s ready to capture traffic.  
![Screenshot 2025-06-02 121419](https://github.com/user-attachments/assets/e8488af5-ef34-4bd6-8c51-ca73d2c701c0)

---    

### 🌐 Step 3: Generate Traffic  
- Browse a website or run a network command to generate some traffic.**(eg.Vulneweb)** 
![image](https://github.com/user-attachments/assets/cf675344-4c1a-473e-8797-4b7ec0e50866)

---    

### 🔎 Step 4: Apply Filters  
- Use protocol filters (e.g., `http`, `dns`, `tcp`) to focus your analysis.  
![Screenshot 2025-06-02 120232](https://github.com/user-attachments/assets/55623e7b-bae5-44a3-9ac7-2358397d5cd6)
![Screenshot 2025-06-02 120541](https://github.com/user-attachments/assets/db7aa4c7-d8be-4edd-9332-0d362bd2eede)
![Screenshot 2025-06-02 120606](https://github.com/user-attachments/assets/3e106ba0-283d-4310-8bc7-99d2f85af7e3)

---  

### 🛑 Step 5: Stop the Capture  
- After a few moments, stop the capture to analyze the results.  

---

### 📑 Step 6: Review Packet Details  
- Examine individual packet details to understand the structure and flow of the data.
- Export the analyse to .pcap format `File>Export specific packets>Choose the file type>Save`.

---  

## 📝 Summary  

The captured packet analysis reveals essential insights into network communications:  
- **💡 Findings**: The captured traffic displayed consistent data exchange, no signs of packet loss or retransmissions, and overall stable network conditions during the capture period.
- **📊 Protocol Hierarchy**: The traffic included diverse protocols, highlighting the use of TCP/IP, HTTP, and other layers relevant to web and application traffic.  
- **🤝 TCP Three-Way Handshake**: A clear and successful handshake was observed between the client and server, ensuring reliable communication was established.  
- **🔍 Detailed Packet Information**: Analysis of Ethernet, IP, and TCP headers revealed expected device interactions, confirming legitimate traffic flows and helping to detect potential anomalies in real-world scenarios.    

---
