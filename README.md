
# 🌐 Multi-Campus Enterprise Network Design (Cisco Packet Tracer)

## 📌 Project Overview

This project demonstrates the design and implementation of a **Multi-Campus Enterprise Network** using Cisco Packet Tracer.
It simulates a real-world organizational network consisting of a **Main Campus and Branch Campus**, connected through routers, switches, VLANs, and WAN links.

The network ensures efficient communication between multiple departments such as Admin, HR, Finance, IT, and Student Labs.

---

## 🎯 Objectives

* Design a scalable multi-campus network
* Implement VLAN-based segmentation
* Configure inter-VLAN routing
* Establish WAN connectivity between campuses
* Simulate cloud-based services (Email Server)
* Test and validate network communication

---

## 🛠️ Technologies Used

* Cisco Packet Tracer
* Networking Devices (Routers, Switches, PCs)
* VLAN (Virtual LAN)
* TCP/IP Protocol
* IPv4 Addressing

---

## 🏗️ Network Topology

![Network Topology](screenshots/topology.png)

---

## 🧩 Network Structure

### Main Campus

* Multiple buildings (A, B, C)
* Departments:

  * Admin
  * HR
  * Finance
  * Business
  * IT
  * Student Lab

### Branch Campus

* Staff VLAN
* Student Lab VLAN

---

## 🔢 VLAN Configuration

| VLAN ID | Department  |
| ------- | ----------- |
| 10      | Admin       |
| 20      | HR          |
| 30      | Finance     |
| 40      | Business    |
| 50      | E&C         |
| 60      | A&D         |
| 70      | Student Lab |
| 80      | IT          |
| 90      | Staff       |
| 100     | Branch Lab  |

---

## 🌍 IP Addressing

* Each VLAN has its own subnet (192.168.x.0/24)
* WAN Link: 10.10.10.0/30
* Cloud Network: 20.0.0.0/30

---

## ⚙️ Key Features

* VLAN segmentation for security
* Inter-VLAN routing using Layer 3 Switch
* Multi-campus connectivity
* Cloud integration (Email Server)
* Scalable network design

---

## 🧪 Testing

✔ Successful ping between VLANs
✔ Communication between campuses
✔ Server connectivity verified

![Ping Test](screenshots/ping-test.png)

---

## 🚀 Future Enhancements

* Add Firewall & Security (ACLs)
* Implement Dynamic Routing (OSPF)
* Add Wireless Network
* Deploy on real hardware

---

## 📚 References

* Cisco Networking Academy
* Packet Tracer Documentation
* Computer Networking Books

---

## 👨‍💻 Author

**Rohit Gupta**
MCA Student

---
