# Network VAPT Report – Metasploitable2 Lab

This repository contains a Network Vulnerability Assessment and Penetration Testing (VAPT) report conducted in a controlled lab environment using Metasploitable2.

---

## 📄 Assessment Details

**Target:** Metasploitable2  
**Environment:** Local Lab / Controlled Setup  
**Assessment Type:** Network Security Testing  
**Author:** Aditya Malode  

---
Vulnerability-Assessment-and-Penetration-Testing-on-Metasploitable-2
The Metasploitable virtual machine is a purposefully vulnerable version of Ubuntu Linux that may be used to test security tools and demonstrate common flaws. This virtual machine’s version 2 is now available for download, and it contains even more vulnerabilities than the initial image. VMWare, VirtualBox, and other popular virtualization platforms are all compatible with this virtual machine. The network interfaces of Metasploitable are bound to the NAT and Host-only network adapters by default, and the image should never be exposed to a hostile network. This Virtual Machine (Metasploitable2) can be used to conduct security training, test security tools, and practice common penetration testing techniques.

---
Pre-requirements
First, we need to download VMWare Workstation Pro or VirtualBox (your choice of selection). It enables users to create and run Virtual Machines (VMs) directly on a single Windows or Linux desktop or laptop, where we can run any Operating System through this software on another Operating System. In this walkthrough, I am using VMWare Workstation Pro to set up the Metasploitable-2 on my computer.

---
VMWare Workstation Pro: VMWare Workstation Pro Download
VirtualBox: VirtualBox Download
Now you can download the Kali Linux OS for attacking the machine.

---
Kali Linux: Kali Linux Download
Downloading and Setting up Metasploitable-2
Now we need to download the Metasploitable-2 image to our system. The compressed file is about 800 MB and can take a while to download over a slow connection. After you have downloaded the Metasploitable-2 file, you will need to unzip the file to see its contents.

---
Download Metasploitable-2:
Rapid7 Metasploitable Download
SourceForge Metasploitable Download
After downloading the Metasploitable2 Image, open VMWare Workstation Pro and follow these steps to set up Metasploitable2:

---
Click on the "Open a Virtual Machine" button.
Select the Metasploitable2 image and click the "Open" button.
Screenshot ``

Now power on this virtual machine.
Screenshot

Now this machine starts…
Screenshot

Default passwords for Metasploitable2 are:

Username: msfadmin
Password: msfadmin
Then the machine starts after entering the credentials …

Screenshot

Find machine IP address by using the following command in terminal:

ifconfig
Screenshot

---
## 🛡️ Objective

The objective of this assessment was to identify and analyze security vulnerabilities present in the Metasploitable2 vulnerable virtual machine.

The test focused on:

- Network discovery  
- Port scanning & service enumeration  
- Vulnerability identification  
- Exploitation validation  
- Risk & impact analysis  

---

## 🔍 Methodology

The assessment followed a structured penetration testing approach:

1. Reconnaissance  
2. Port Scanning  
3. Service Enumeration  
4. Vulnerability Analysis  
5. Exploitation  
6. Risk Evaluation  
7. Documentation  

---

## 🧰 Tools Used

- Nmap  
- Netcat  
- Metasploit Framework  
- Burp Suite (where applicable)  
- Linux utilities  

---

## 🚨 Key Findings (Summary)

Examples of identified issues may include:

- Open & vulnerable network services  
- Weak authentication mechanisms  
- Outdated software components  
- Misconfigured services  
- Exploitable remote services  

*(Refer to full report for technical details.)*

---

## 📑 Full Report

👉 **View the complete VAPT Report:**  
[Open Network VAPT Report](./NETWORK%20VAPT%20REPORT%20BY%20Aditya%20malode%20(1).pdf)

---

## ⚠️ Disclaimer

Metasploitable2 is an intentionally vulnerable machine designed for security training.

This assessment was performed strictly for **educational purposes** in a controlled lab environment.

---

## 👤 Author

**Aditya Malode**  
Aspiring Cybersecurity Analyst  
Focus: VAPT | Web Security | Network Security
