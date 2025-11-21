# Request for Proposal (RFP) — Wireless Infrastructure Deployment

**Organization:** Peekaboo  
**Prepared For:** MITT — Network & System Administration Program  
**Contact:** Justin Ducharme — justin.ducharme@mitt.ca  
**Submission Deadline:** 2025-11-20 18:13  
**Submission Format:** PDF / Markdown (GitHub Repository)

---

## 1. Executive Summary
Peekaboo seeks qualified vendors to design, deploy, and support a modern wireless infrastructure across its office premises. The upgraded wireless system must support Wi-Fi 6 standards, provide secure authentication (WPA3, 802.1X), ensure high-capacity access for staff and guest devices, and integrate seamlessly with the existing wired network.

The awarded vendor will conduct a full site survey, deploy hardware, validate performance, document the solution, and provide ongoing technical support.

---

## 2. Background / Current Environment
Peekaboo’s office consists of multiple rooms, work areas, hallways, and meeting spaces. The current environment includes:

- Existing wired network with VLAN segmentation  
- Cat6 PoE cabling  
- No centralized wireless controller  
- Mixed construction materials (drywall, glass, concrete)  
- Existing network rack and cable pathways  

The organization requires a scalable, reliable, and secure Wi-Fi 6 solution for daily business operations.

---

## 3. Scope of Work

### 3.1 Site Survey
- Conduct wireless survey using Ekahau or equivalent tools  
- Measure RF interference and signal attenuation  
- Produce predictive and post-deployment heatmaps  
- Provide AP placement, antenna type, and installation recommendations  

### 3.2 Installation & Configuration
- Install Wi-Fi 6 access points across specified areas  
- Perform PoE cabling, mounting, and labeling  
- Configure SSIDs: Employee, Guest, IoT  
- Apply VLAN segmentation for each SSID  
- Configure WPA3 security, 802.1X authentication, and MAC filtering  
- Implement QoS for voice/video applications  

### 3.3 Integration with Existing Wired Network
- Configure VLANs, switch ports, and trunking  
- Ensure routing and DHCP compatibility  
- Validate seamless roaming between APs  
- Document all network configuration changes  

### 3.4 Ongoing Maintenance & Support
- Hardware warranty (minimum 1 year)  
- Regular firmware/security updates  
- Remote and onsite technical support  
- Performance optimization reports  

---

## 4. Technical Requirements

### 4.1 Coverage & Performance
- 100% coverage across office areas  
- ≥95% of areas with RSSI ≥ -67 dBm  
- Minimum 50 Mbps per client under normal load  
- Seamless roaming with handoff <50 ms  
- Support for 300+ simultaneous devices  

### 4.2 Wireless Standards
- IEEE 802.11ax (Wi-Fi 6) compliant  
- Backward compatible with 802.11ac/n  
- Supports MU-MIMO and OFDMA  

### 4.3 Security Requirements
- WPA3 Personal or WPA3-Enterprise  
- Support for 802.1X authentication  
- MAC address filtering  
- Guest network isolation and firewall segmentation  
- Logging with optional SIEM integration  

### 4.4 Network Management
- Centralized controller (cloud or on-prem)  
- Real-time monitoring and alerts  
- SNMPv3, Syslog, and REST API support  
- Automated backups and update scheduling  

### 4.5 Scalability
- System must support future AP expansion  
- Controller licensing must support scaling  

---

## 5. Deliverables
- Site survey report  
- Heatmaps (predictive & validated)  
- Bill of Materials (BOM)  
- AP placement and network design diagrams  
- SSID, VLAN, and security configuration documents  
- Acceptance testing report  
- Administrator training & guide  
- Final deployment documentation  

---

## 6. Acceptance Criteria & Testing

| Test Category | Requirement |
|--------------|-------------|
| Coverage | ≥ 95% at -67 dBm or better |
| Throughput | ≥ 50 Mbps per user |
| Roaming | < 50 ms handoff delay |
| Authentication | 100% success (WPA3/802.1X) |
| Guest Isolation | No access to internal VLANs |

**Testing Tools:** Ekahau Analyzer, AirMagnet, iPerf3, Wireshark.

---

## 7. Vendor Qualifications
- Minimum 2 years enterprise wireless deployment experience  
- 2+ similar scale projects completed  
- Certifications: CCNA/CCNP Wireless, CWNA, ACMP, Network+  
- 3 customer references with contact details  
- Ability to provide ongoing technical support  

---

## 8. Project Timeline

| Phase | Duration | Deliverable |
|-------|----------|-------------|
| Site Survey | 1 week | Survey report |
| Procurement | 2–3 weeks | Hardware delivery |
| Installation | 1–2 weeks | AP deployment |
| Configuration | 3–5 days | Configuration completed |
| Testing & Optimization | 1 week | Test report |
| Training & Documentation | 2 days | Final documentation |

**Total Duration:** 5–7 weeks

---

## 9. Cost & Pricing Requirements

Vendors must include detailed cost breakdowns:

- Access point hardware  
- Wireless controller licenses  
- Installation labor  
- Shipping/travel costs  
- Annual support & maintenance fees  

### Example Pricing Table

| Item | Qty | Unit Price | Total |
|------|-----|------------|-------|
| Wi-Fi 6 Access Point | 12 | $XXX | $XXX |
| Controller License | 1 | $XXX | $XXX |
| Installation Labor | - | $XXX | $XXX |
| Support (1 Year) | - | $XXX | $XXX |

---

## 10. Evaluation Criteria

| Category | Weight |
|----------|--------|
| Technical Proposal | 40% |
| Cost Competitiveness | 30% |
| Vendor Experience | 10% |
| Support & Warranty | 10% |
| Timeline & Delivery Plan | 10% |

---

## 11. Terms & Conditions
- All proposals become the property of Peekaboo  
- Vendor must maintain confidentiality and data protection  
- Peekaboo may reject any/all proposals  
- Payment terms: 30% upfront, 70% after acceptance  

---

## 12. Appendices
- Appendix A: Office Floor Plan  
- Appendix B: Existing Network Diagram  
- Appendix C: Vendor Submission Template  
- Appendix D: Equipment Datasheets  

---

# End of Document
