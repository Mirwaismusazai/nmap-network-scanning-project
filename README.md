# nmap-network-scanning-project
# 🔍 Nmap Network Scanning Project

## 📌 Overview
This project showcases **network reconnaissance** using **Nmap**, one of the most powerful network scanning tools.  
The objective is to **identify active hosts, scan for open ports, and detect running services** in a subnet.  

This is useful for **penetration testing, network security audits, and cybersecurity research**.  

---

## 🚀 Features & Methodology
This project follows a **structured scanning process**:

### **🛠 Step 1: Host Discovery (Identifying Active Devices)**
![Nmap assignment _page-0001](https://github.com/user-attachments/assets/cb356a37-3a50-4d5e-918b-7eee0fa94b90)

### **🛠 Step 2: Fast Port Scanning & Network Discovery**
#### **Command Used:**
bash
nmap -F -Pn -n [target]/24

#### **Purpose:**
- **Quickly scans common ports** instead of all 65,535.
- **Skips ping checks** to assume all hosts are up.
- **Speeds up the scan** by disabling DNS resolution.
- ![Nmap assignment _page-0002](https://github.com/user-attachments/assets/fcd44f71-7903-4bc0-9f2c-97a8f8e93c13)


### **🛠 Step 3: Revalidating Active Hosts**
#### **Command Used:**
bash
nmap -sn [target]/24

#### **Purpose:**
- **Double-checks** active hosts detected earlier.
- Ensures **no inconsistencies** in network mapping.
- Confirms **latency values and MAC addresses**.
- ![Nmap assignment _page-0003](https://github.com/user-attachments/assets/ecbb135d-2ccc-4b8a-8343-f472ce14943c)

- ### **🛠 Step 4: Service & Version Detection**
#### **Command Used:**
bash
nmap -sV [target]/24

#### **Purpose:**
- **Identifies running services** on open ports.
- **Detects software versions**, helping find vulnerabilities.
- Useful for **penetration testing & security audits**.
- ![Nmap assignment _page-0004](https://github.com/user-attachments/assets/36049862-4016-4c84-bc2f-f4675602e7d2)

### **🛠 Step 5: Deep Port & Service Analysis**
#### **Command Used:**
bash
nmap -sV [target]/24

#### **Purpose:**
- Further **analyzes open ports** and running services.
- Detects **misconfigured or outdated services**.
- Provides **detailed security insights**.
- ![Nmap assignment _page-0005](https://github.com/user-attachments/assets/59541733-95b5-4268-a81f-712f3edb7099)

- ## 🔥 Why This Project Matters
✅ **Essential for network security** – Helps identify security flaws.  
✅ **Useful for penetration testing** – Finds open ports & services.  
✅ **Real-world cybersecurity skills** – Shows practical Nmap usage.  

---




