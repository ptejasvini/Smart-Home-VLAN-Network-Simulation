
# 🏠 Smart Home VLAN Network Simulation (CCNA Project)

This is a Cisco Packet Tracer-based Smart Home VLAN network project designed for CCNA learners and networking enthusiasts. The project simulates a segmented smart home network using VLANs, showcasing inter-VLAN routing with a multilayer switch.

---

## 📁 Project Files
- `Smart_Home_VLAN_Simulation.pkt` – Packet Tracer simulation file
- `README.md` – Project documentation and configuration guide

---

## 🌐 Network Design Overview

### Devices Used:
- 1 × Router (2911)
- 1 × Multilayer Switch (3560-24PS)
- 6 × PCs (representing Smart Devices, Security Devices, Personal Devices, Admin)

### VLANs Configured:
| VLAN ID | Name        | Devices                  |
|---------|-------------|--------------------------|
| 10      | IoT         | Smart_Light, Thermostat  |
| 20      | Security    | CCTV_Camera              |
| 30      | Personal    | Laptop, Mobile           |
| 99      | Management  | Admin_PC                 |

### IP Schema:
| VLAN | Gateway IP     | Device IPs               |
|------|----------------|--------------------------|
| 10   | 192.168.10.1   | 192.168.10.10-11         |
| 20   | 192.168.20.1   | 192.168.20.10            |
| 30   | 192.168.30.1   | 192.168.30.10-11         |
| 99   | 192.168.99.1   | 192.168.99.10            |

---

## ⚙️ Configuration Highlights

- VLANs created and assigned to specific interfaces on the switch.
- Inter-VLAN routing enabled using `ip routing` on the multilayer switch.
- Static IPs assigned to all PCs to simulate real device segregation.

---

## 🧪 How to Use

1. Open the `.pkt` file in Cisco Packet Tracer.
2. Review the VLAN assignments and IP configurations.
3. Ping across devices in the same and different VLANs.
4. (Optional) Extend the network with DHCP, ACLs, or wireless devices.

---

## 📜 License

This project is open-source and free to use for educational purposes.
