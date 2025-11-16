
# 🏠 Home Network Setup & Troubleshooting Project

A hands-on project focused on setting up a home Wi-Fi network, configuring devices, and performing basic troubleshooting tasks.  
This project was completed to build practical ICT support skills relevant to entry-level IT roles and school ICT environments.

---

## 📡 Network Overview

The home network used in this project included:

- Wi-Fi router (2.4GHz & 5GHz bands)
- **Secondary Wi-Fi Network (additional SSID)**
- Windows laptop (Windows 10/11)
- Smartphone (Android/iOS)
- Smart TV / additional device

The goal was to configure the network, test device connectivity, and practise troubleshooting.

---

## 🔧 Wi-Fi Configuration

### ✔ Accessed Router Admin Panel  
Logged into the router using its local IP (`192.168.x.x`) to modify wireless settings.

### ✔ Configured Wireless Networks  
- Updated SSID names for easier identification  
- Enabled WPA2/WPA3 security  
- Set up a **secondary Wi-Fi network**  
- Selected 2.4GHz/5GHz bands  
- Applied configuration changes and rebooted router

### ✔ Connected Devices  
Multiple devices were connected to verify compatibility and stability across both networks.

---

## 📶 Connectivity Testing

### Tests performed:
- **Ping test** to check latency (`ping google.com`)
- **Wi-Fi signal strength** checks
- **Browser load tests**
- **Network switching** between main and secondary SSIDs

---

## 🛠 Troubleshooting Commands Used

```bash
ipconfig /flushdns    # Clear DNS cache
ipconfig /release     # Release current IP
ipconfig /renew       # Request new IP
ipconfig /all         # View full network configuration
ping google.com       # Test network connectivity
