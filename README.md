# 0.1 Zogu Cybersecurity Home Lab Setup

Welcome to my cybersecurity testing lab! This project documents the step-by-step process I used to set up a virtual lab for hands-on learning in ethical hacking, penetration testing, and cyber defense.

---

## 🧰 Tools Used

| Tool | Purpose | Link |
|------|---------|------|
| **Oracle VirtualBox** | Virtualization software for creating and running virtual machines | [Download](https://www.virtualbox.org/wiki/Downloads) |
| **Windows 10 ISO** | Operating system to simulate a real-world target or endpoint | [Download](https://www.microsoft.com/en-ca/software-download/windows10) |
| **Kali Linux (VirtualBox Image)** | Offensive security-focused Linux distro used for penetration testing | [Download](https://kali.download/base-images/kali-2025.1c/kali-linux-2025.1c-virtualbox-amd64.7z) |
| **7-Zip File Manager** | File extractor for compressed Kali image | [Download](https://www.7-zip.org/) |

---

## 🛠️ Setup Process

### 1. Install Oracle VirtualBox
- Download and install Oracle VirtualBox.
- Use the default settings.

### 2. Create Windows 10 Virtual Machine
- Open VirtualBox > Click **"New"**.
- Name the VM (avoid using names similar to your host OS).
- Select the downloaded Windows ISO as the startup disk.
- Check **"Skip Unattended Installation"**.
- Complete the setup using the default settings.

### 3. Import Kali Linux Virtual Machine
- Use 7-Zip to extract the Kali `.7z` file.
- Open the extracted `.vbox` file with VirtualBox.
- Start the VM and log in using:
  - **Username**: `kali`
  - **Password**: `kali`

---

## 🧠 Why This Lab Matters

This lab serves as a safe environment to:
- Practice real-world cyber attacks
- Run vulnerable machines and test security tools
- Learn system hardening, detection, and defense
- Build a strong cybersecurity portfolio

## 📷 Screenshots

### VirtualBox VM Dashboard  
![VM Dashboard](https://github.com/Zogu101/Zogu-security-lab/blob/main/vm%20machine.png)

### Kali Linux VM  
![Kali VM Screen](https://github.com/Zogu101/Zogu-security-lab/blob/main/Kali.png)

### Windows 10 VM 
![Windows VM screen](https://github.com/Zogu101/Zogu-security-lab/blob/main/Windows.png)

