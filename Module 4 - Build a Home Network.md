# 🏠 NetAcad – Junior Cybersecurity Analyst Career Path

## Home Network Setup and Configuration

This repository documents my hands-on activity from the **Cisco Networking Academy (NetAcad) Junior Cybersecurity Analyst Career Path**. The activity focuses on connecting network devices, configuring a home wireless router, setting up wireless security, and testing network connectivity using Cisco Packet Tracer.

## 🎯 Objectives

- Connect devices using appropriate network cables.
- Configure a home wireless router.
- Set up DHCP and wireless LAN settings.
- Configure wired and wireless client devices.
- Test internet connectivity across the network.

## 📋 Background / Scenario

Natsumi asked for assistance in setting up her new home network using a cable TV provider. The task involved connecting the cable modem, TV, PCs, laptop, and wireless router. It also required configuring DHCP, securing the wireless network, and ensuring that all devices could access the internet.

# 📁 Packet Tracer Activity File

📥 [Download Packet Tracer Activity (.pka)](https://github.com/CedPad/Netacad-Junior-Cybersecurity-Analyst-Career-Path/raw/refs/heads/main/Configure%20a%20Wireless%20Router%20and%20Client.pka)

---

## 🛠️ Activity Walkthrough

<details>
<summary><strong>📌 Part 1: Connect the Devices</strong></summary>

### Step 1: Connect the Coaxial Cables

Connected the cable splitter to the cable modem using the Coaxial1 port and to the TV using the Coaxial2 port. Turned on the TV to verify that the connection was successful and the TV program appeared.

### Step 2: Connect the Network Cables

Used copper straight-through cables to connect Port 1 of the cable modem to the Internet port of the Home Wireless Router. Connected the Office PC to GigabitEthernet 1 and the Bedroom PC to GigabitEthernet 2 of the router. This established the wired home network connection.

### 📷 Screenshot

![Part 1 - Network Connections](https://github.com/user-attachments/assets/a0425320-0940-4e66-8e84-abbd0b85ad02)

</details>

<details>
<summary><strong>📌 Part 2: Configure the Wireless Router</strong></summary>

### Step 1: Access the Home Wireless Router GUI

Configured the Office PC to obtain an IP address automatically using DHCP. Identified the default gateway address and entered it into the web browser to access the Home Wireless Router GUI. Logged in using the default credentials.

### Step 2: Configure Basic Settings

Changed the DHCP maximum number of users to 10 to limit the number of devices that could connect to the network. Then, accessed the Administration settings and changed the default administrator password to improve router security.

### Step 3: Configure a Wireless LAN

Enabled the 2.4 GHz wireless network and changed its SSID from Default to **MyHome**. Configured wireless security by selecting **WPA2 Personal** and setting a Wi-Fi passphrase. Saved the settings to complete the wireless network configuration.

### 📷 Screenshots

**Accessing the Router GUI**

![Router GUI](https://github.com/user-attachments/assets/da60d7f0-fb78-4cdb-ac2a-ab67f25077ed)

**Basic Router Settings**

![Basic Settings](https://github.com/user-attachments/assets/24b628b0-c3a4-4287-b701-bc61cbe3d12e)

**Wireless LAN Configuration**

![Wireless Configuration](https://github.com/user-attachments/assets/fed118f7-7ed2-42ca-ad4a-922b468e9541)

</details>

<details>
<summary><strong>📌 Part 3: Configure IP Addressing and Test Connectivity</strong></summary>

### Step 1: Connect the Laptop to the Wireless Network

Connected the living room laptop to the previously configured **MyHome** wireless network using the assigned Wi-Fi passphrase. Verified the connection through the Link Information tab and tested internet access by opening `skillsforall.srv` in the web browser.

### Step 2: Test Connectivity from the Office PC

Opened the web browser on the Office PC and accessed `skillsforall.srv` to verify that the wired network connection was properly configured and had internet access.

### Step 3: Configure the Bedroom PC

Configured the Bedroom PC to obtain its IP address automatically through DHCP. Verified that it received an IP address starting with `192` and tested its internet connectivity by accessing `skillsforall.srv`.

### 📷 Screenshots

**Laptop Wireless Connection**

![Laptop Connection](https://github.com/user-attachments/assets/2ea614dc-5df1-4ee1-b38e-3725713fe329)

**Office PC Internet Connectivity**

![Office PC](https://github.com/user-attachments/assets/747ca855-fe8c-490b-8017-646c751a6439)

**Bedroom PC Configuration**

![Bedroom PC](https://github.com/user-attachments/assets/b17741e5-fab0-48b3-9f5d-d5df0d6f4f4f)

</details>

---

## ✅ Conclusion

Successfully completed the home network setup by connecting the necessary devices, configuring the wireless router, enabling DHCP, and securing the wireless LAN using WPA2 Personal. Tested connectivity on all client devices and verified that the laptop, Office PC, and Bedroom PC could access the internet.

---

**Platform:** Cisco Packet Tracer  
**Learning Path:** Cisco Networking Academy – Junior Cybersecurity Analyst Career Path  
**Activity:** Home Network Setup and Configuration
