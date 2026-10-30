# 📅 Week 1: Virtual Environment Deployment

The primary objective for the first week was to establish a secure, interconnected virtual lab using Oracle VirtualBox to simulate a real-world network.

---

## 🛠️ Lab Configuration Steps

### 1. Virtual Machine Provisioning
Deployed the core operating systems required for the lab, specifically setting up Kali Linux alongside Windows environments (Win10 and Win11) to act as testing targets.

> ![VirtualBox Dashboard](path/to/virtualbox-dashboard.png)  
> *[Insert VirtualBox dashboard screenshot here]*

### 2. Network Architecture Setup
Linked all deployed virtual machines to a unified, internal network configuration by utilizing VirtualBox's NAT Network feature. This ensures isolation while allowing inter-VM communication.

> ![NAT Network Settings](path/to/nat-network-settings.png)  
> *[Insert NAT Network settings screenshot here]*

### 3. IP Addressing Configuration
Assigned specific, static IP addresses to the machines to establish a controlled network topology within the 10.0.0.0/24 subnet.

* **Kali Linux Node:** `10.0.0.2/24`
* **Windows Node:** `10.0.0.11/24`

> ![Kali Linux IP Configuration](path/to/kali-ip-config.png)  
> *[Insert Kali Linux IP configuration screenshot here]*

### 4. Connectivity Verification
Validated the network setup by executing ICMP echo requests (ping) to ensure successful bidirectional communication between the attacker (Kali) and target (Windows) machines.

* **Testing from Windows to Kali:**
  > ![Windows Ping](path/to/windows-ping.png)  
  > *[Insert Windows ping screenshot here]*

* **Testing from Kali to Windows:**
  > ![Kali Ping](path/to/kali-ping.png)  
  > *[Insert Kali ping screenshot here]*

---

## 🚀 5. Next Steps
With the network foundation solid, the lab is fully operational and prepared for the upcoming practical cybersecurity modules.

---

## 💻 Technical Stack
* **Virtualization Platform:** Oracle VirtualBox
* **Operating Systems:** Kali Linux, Windows 10/11
* **Network Protocols & Concepts:** NAT Network, Static IP Assignment, ICMP

---

## 🤝 Connect
* **LinkedIn:** [Your LinkedIn Profile Link]
