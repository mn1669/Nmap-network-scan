# 🔍 Task 1: Scan Your Local Network for Open Ports  

## 📌 Objective  
The goal of this task is to practice **network reconnaissance** by scanning devices in my local network and identifying open ports. This helps understand how services are exposed and why securing ports is important in cybersecurity.  

---

## 🛠 Tools Used  
- **Nmap** → For port scanning  
- **Command Prompt / Terminal** → To find IP range and run scans  
- **Wireshark (Optional)** → To analyze network traffic during scanning  

---

## 📖 Steps I Followed  

1. **Installed Nmap**  
   - Downloaded from [nmap.org](https://nmap.org/download) and installed it.  

2. **Found my local IP range**  
   - Used the following command:  
     - Windows → `ipconfig`  
     - Linux/Mac → `ifconfig` or `ip addr`  
   - Found my IP (e.g., `192.168.1.32`) and subnet mask (`255.255.255.0`).  
   - Network range calculated as **192.168.1.0/32**.  or Try for 
   - e.g., (nmap -sS 45.33.32.156) 

3. **Ran a TCP SYN scan**  
   ```bash
   nmap -sS 192.168.1.0/24 or nmap -sS 45.33.32.156
4. **My IP address is completely safe. All scans, tests, and experiments are performed locally on my system, ensuring that no personal or public IPs are exposed and your privacy is fully protected**.

