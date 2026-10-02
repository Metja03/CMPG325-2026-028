# CMPG325 Computer Networks Project

## Ipeleng Study & Tutoring Hub

Student:LAMOLA MC  
Student Number: 40624102  
Client: Ipeleng Study & Tutoring Hub  
Location: Kimberley, South Africa

---

## 1. Project Overview

This project presents the design and implementation of a computer
network for Ipeleng Study & Tutoring Hub in Kimberley.

The network separates staff, students, guests and network management
traffic using VLAN segmentation. Router-on-a-stick is used to provide
inter-VLAN routing, while DHCP provides automatic IP addressing for
end-user networks. A dedicated guest wireless network is also
implemented.

---

## 2. Client Requirements

The network was designed to provide:

- Separate staff, student and guest networks
- Network management through a dedicated management VLAN
- VLAN-based network segmentation
- DHCP for end-user devices
- Guest wireless access
- Support for future user growth
- Minimal physical infrastructure changes



## 3. VLAN and IP Addressing

| VLAN | Purpose | Network | Gateway |
|---|---|---|---|
| 10 | Staff | 172.30.10.0/25 | 172.30.10.1 |
| 20 | Students | 172.30.10.128/25 | 172.30.10.129 |
| 30 | Guests | 172.30.11.0/26 | 172.30.11.1 |
| 99 | Management | 172.30.11.64/27 | 172.30.11.65 |



## 4. Network Technologies

- Cisco Packet Tracer
- Cisco 1941 router
- Cisco 2960 switches
- VLANs
- 802.1Q trunking
- Router-on-a-stick
- DHCP
- Wireless access point
- Static IP addressing



## 5. Network Topology

The complete network topology is available in the Evidence folder.



## 6. Assigned Technical Feature

The assigned networking feature is VLAN segmentation.

VLANs were implemented to logically separate staff, student,
guest and management traffic.



## 7. Testing and Verification

The implementation was tested using:

- VLAN verification
- Trunk verification
- Router interface verification
- DHCP verification
- End-device IP verification
- Ping/connectivity testing
- Guest wireless testing

Supporting screenshots are available in the Evidence folder.



## 8. Project Files

### Documentation

The project reports are available in the Documentation folder.

### Packet Tracer

The completed Packet Tracer implementation is available in the
Packet-Tracer folder.

### Evidence

Configuration and testing screenshots are available in the Evidence folder.



## 9. Conclusion

The implemented network provides segmented connectivity for staff,
students and guests while providing a dedicated management network.
The design uses VLANs, router-on-a-stick, DHCP and wireless access
to meet the identified client requirements and support future growth.
