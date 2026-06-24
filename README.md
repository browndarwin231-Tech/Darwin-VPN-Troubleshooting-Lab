# Darwin VPN Troubleshooting Lab

## Overview

This project demonstrates a common Windows 11 Help Desk troubleshooting scenario involving VPN connection issues.

The lab walks through identifying VPN connectivity problems, testing network connectivity, verifying DNS resolution, checking ports, and documenting the troubleshooting process using built-in Windows tools.

---

## Skills Demonstrated

- Windows 11 Administration
- Help Desk Troubleshooting
- VPN Troubleshooting
- Network Diagnostics
- DNS Troubleshooting
- Command Prompt
- PowerShell
- Customer Support Documentation

---

## Tools Used

- Windows 11
- VPN Settings
- Command Prompt
- Windows PowerShell
- Network Connections
- Task Manager

---

## Troubleshooting Steps

### 1. Verify Internet Connection

Confirmed the computer has internet access before testing VPN connectivity.

---

### 2. Review VPN Settings

Verified VPN server address, username, authentication method, and connection settings.

---

### 3. Check IP Configuration

Used **ipconfig /all** to verify adapter configuration.

---

### 4. Test Network Connectivity

Used **ping** to verify communication with public hosts.

---

### 5. Trace Network Route

Used **tracert** to identify possible routing problems.

---

### 6. Verify DNS Resolution

Used **nslookup** to confirm DNS was functioning correctly.

---

### 7. Test VPN Port Connectivity

Used PowerShell **Test-NetConnection** to verify VPN port accessibility.

---

### 8. Document Resolution

Recorded troubleshooting steps and final resolution.

---

## Screenshots

### 1. VPN Settings

Reviewed Windows VPN configuration.

![VPN Settings](screenshots/01-vpn-settings.png)

---

### 2. Network Connections

Verified active network adapters.

![Network Connections](screenshots/02-network-connections.png)

---

### 3. IP Configuration

Verified adapter information using ipconfig.

![IP Configuration](screenshots/03-ipconfig.png)

---

### 4. Ping Test

Verified internet connectivity.

![Ping Test](screenshots/04-ping-test.png)

---

### 5. Tracert

Analyzed the network path.

![Tracert](screenshots/05-tracert.png)

---

### 6. NSLookup

Verified DNS resolution.

![NSLookup](screenshots/06-nslookup.png)

---

### 7. Test-NetConnection

Verified VPN server port accessibility.

![Test-NetConnection](screenshots/07-test-netconnection.png)

---

### 8. Resolution Summary

Final troubleshooting documentation.

![Resolution](screenshots/08-resolution.png)
