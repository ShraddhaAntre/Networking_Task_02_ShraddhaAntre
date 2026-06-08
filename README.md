# Network Task 02 - Network Devices & IP Addressing

## Objective
The purpose of this task is to understand common network devices, IP addressing concepts, and how data travels within a network.

---

# Part A: Network Devices Research

## 1. Router

### Purpose
A router connects different networks and forwards data between them.

### How It Works
It receives data packets and sends them to the correct destination using IP addresses.

### Real-World Usage
Used in homes, offices, and organizations to provide internet access.

---

## 2. Switch

### Purpose
A switch connects multiple devices within the same network.

### How It Works
It uses MAC addresses to send data directly to the intended device.

### Real-World Usage
Used in offices, schools, and computer labs.

---

## 3. Hub

### Purpose
A hub connects multiple devices in a network.

### How It Works
It broadcasts incoming data to all connected devices.

### Real-World Usage
Older local area networks (LANs).

---

## 4. Access Point

### Purpose
Provides wireless connectivity to devices.

### How It Works
Converts wired network signals into wireless signals.

### Real-World Usage
Wi-Fi networks in homes, offices, and public places.

---

## 5. Firewall

### Purpose
Protects networks from unauthorized access and cyber threats.

### How It Works
Monitors and filters incoming and outgoing network traffic.

### Real-World Usage
Used in personal computers, routers, and enterprise networks.

---

## 6. Modem

### Purpose
Connects a network to an Internet Service Provider (ISP).

### How It Works
Converts digital signals into transmission signals and vice versa.

### Real-World Usage
Used in homes and offices for internet connectivity.

---

# Part B: IP Address Classification

| IP Address | Type | Reason |
|------------|------|---------|
| 192.168.1.10 | Private | Belongs to 192.168.0.0 – 192.168.255.255 private range |
| 10.0.0.5 | Private | Belongs to 10.0.0.0 – 10.255.255.255 private range |
| 172.16.5.20 | Private | Belongs to 172.16.0.0 – 172.31.255.255 private range |
| 8.8.8.8 | Public | Public Google DNS address |
| 1.1.1.1 | Public | Public Cloudflare DNS address |
| 192.168.100.1 | Private | Belongs to 192.168.x.x private range |

---

# Part C: Understanding Your Network

## IPv4 Address
(Add your IPv4 address here)

## Default Gateway
(Add your gateway here)

## DNS Server
(Add your DNS server here)

### Answers

#### Which IP range does your device belong to?
My device belongs to the private IP address range.

#### Is it Public or Private?
Private IP Address.

#### What role does your router play in your network?
The router connects my local network to the internet and forwards data between devices and external networks.

#### What would happen if the DNS server stopped working?
Websites would not open using domain names because the DNS server converts domain names into IP addresses.

---

# Part D: Network Communication Flow

## Diagram

Your Device
↓
Router
↓
DNS Server
↓
Google Server
↓
Response Back to Device

### Explanation

#### Step 1: Your Device
The user enters www.google.com into the browser.

#### Step 2: Router
The router forwards the request to the DNS server.

#### Step 3: DNS Server
The DNS server translates www.google.com into an IP address.

#### Step 4: Google Server
The request reaches Google's server and the webpage data is prepared.

#### Step 5: Response Back
The server sends the webpage data back to the user's device.

---

# Part E: Practical Command Exercise

## Windows Commands

```cmd
ipconfig /all
nslookup google.com
ping google.com
