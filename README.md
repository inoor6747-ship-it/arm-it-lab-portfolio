# ARM IT Lab Portfolio

## Project Overview
This repository showcases an ARM-compatible IT support and networking troubleshooting lab built with Cisco Packet Tracer, structured documentation, and a help desk-style incident workflow.

The lab was designed to simulate common entry-level IT support issues, including:
- DHCP failures
- DNS resolution problems
- Incorrect default gateway settings
- Physical connectivity failures
- Internal server reachability issues

Each scenario was documented with screenshots, SOPs, and a ticket tracker to reflect a structured support process.

---

## Core Skills Demonstrated
- TCP/IP troubleshooting
- DHCP configuration and validation
- DNS troubleshooting and name resolution testing
- Default gateway and connectivity analysis
- Physical connectivity troubleshooting
- Ticket documentation and incident tracking
- SOP creation and technical documentation
- Windows endpoint troubleshooting fundamentals

---

## Lab Topology
The Packet Tracer lab includes:
- 1 Router (`R1`)
- 1 Switch (`SW1`)
- 3 Client PCs (`PC1`, `PC2`, `PC3`)
- 1 Server (`SRV1`)

### Network Configuration
- Network: `192.168.10.0/24`
- Router IP: `192.168.10.1`
- Server IP: `192.168.10.10`
- DHCP scope start: `192.168.10.100`
- DNS records:
  - `fileserver.local`
  - `helpdesk.local`

---

## Troubleshooting Scenarios Completed
1. DHCP address not assigned
2. DNS name resolution failure
3. Incorrect default gateway
4. Network cable unplugged
5. Cannot reach internal server

---

## Repository Structure
- `PacketTracer/` - Packet Tracer lab file and lab notes
- `Screenshots/` - Topology, configuration, and troubleshooting proof
- `SOPs/` - Standard operating procedures
- `Tickets/` - Help desk incident tracker
- `Endpoint_Notes/` - Windows troubleshooting notes
- `Linux_VM_Notes/` - Planned future Linux VM expansion
- `Resume_Project_Summary.pdf` - Resume-ready project summary

---

## Documentation Links

### Project Summary
- [Resume Project Summary](Resume_Project_Summary.pdf)

### Packet Tracer
- [Packet Tracer Lab File](PacketTracer/ARM_IT_Lab_Base.pkt)
- [Packet Tracer Notes](PacketTracer/PacketTracer_Notes.pdf)

### SOPs
- [DHCP Troubleshooting SOP](SOPs/DHCP_Troubleshooting_SOP.pdf)
- [DNS Troubleshooting SOP](SOPs/DNS_Troubleshooting_SOP.pdf)
- [Gateway Connectivity SOP](SOPs/Gateway_Connectivity_SOP.pdf)
- [Physical Connectivity Troubleshooting SOP](SOPs/Physical_Connectivity_Troubleshooting_SOP.pdf)

### Tickets
- [ARM IT Lab Ticket Tracker](Tickets/ARM_IT_Lab_Tickets.xlsx)

### Endpoint Notes
- [Windows Endpoint Troubleshooting Notes](Endpoint_Notes/Windows_Endpoint_Troubleshooting_Notes.pdf)
- [Local User Support Notes](Endpoint_Notes/Local_User_Support_Notes.pdf)

### Linux VM Notes
- [Planned Linux VM Expansion](Linux_VM_Notes/Planned_Linux_VM_Expansion.pdf)

---

## Screenshot Proof
- [Packet Tracer Topology](Screenshots/packet_tracer_topology.png)
- [PC1 DHCP Address](Screenshots/pc1_dhcp_address.png)
- [SRV1 DHCP Configuration](Screenshots/srv1_dhcp_config.png)
- [SRV1 DNS Configuration](Screenshots/srv1_dns_config.png)
- [Successful Ping Test](Screenshots/successful_ping_test.png)
- [Successful DNS Name Test](Screenshots/successful_dns_name_test.png)
- [Wrong Gateway Issue](Screenshots/wrong_gateway_issue.png)
- [Wrong Gateway Fixed](Screenshots/wrong_gateway_fixed.png)
- [Cable Unplugged Issue](Screenshots/cable_unplugged_issue.png)
- [Cable Unplugged Fixed](Screenshots/cable_unplugged_fixed.png)

---

## Help Desk Workflow
This lab includes a structured ticket tracker to document:
- Ticket ID
- User
- Device
- Issue
- Priority
- Symptoms
- Troubleshooting steps
- Root cause
- Resolution
- Status
- Date closed

The goal was to mirror an entry-level service desk workflow while documenting repeatable troubleshooting steps.

---

## Outcome
This project demonstrates a structured approach to diagnosing, resolving, and documenting common IT support issues in a controlled lab environment. It combines technical troubleshooting, written documentation, and incident tracking into one portfolio project.

---

## Author
**Ibrahim Noor**  
IT Portfolio
