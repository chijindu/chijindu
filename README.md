## Hi, I'm Chijindu  👋

### Senior Network Engineer \| Architect \| Cloud \| Automation \| DevOps

I design, implement, secure, and troubleshoot enterprise and
carrier-grade networks and infrastructure across on-premises, hybrid-cloud, and cloud
environments. Here I document practical engineering projects,
lab work, infrastructure-as-code, and automation 

My focus is on building networks & Infrastructure that is **resilient, secure, scalable,
observable, and repeatable**.


---

## 🔧 What I do

- 🔐 **Network security:** firewall design and migrations, IPsec VPNs, segmentation, policy management at scale
- ☁️ **Cloud networking:** Azure VNets, peering, Virtual Network Gateways, site-to-site VPNs, AWS hybrid connectivity
- ⚙️ **Automation:** Terraform, Ansible and Python to replace manual changes with code
- 🌐 **Routing and data centre:** BGP, OSPF, IS-IS, MPLS, EVPN, VXLAN, Cisco ACI and SD-WAN
- 🛠️ **Escalation and mentoring:** complex troubleshooting, root cause analysis, and turning technical risk into practical business decisions

---


## 🧰 Tech stack

**Automation and IaC:** Terraform · Ansible · Python · Bash · GitLab CI/CD · Docker · Kubernetes

**Cloud:** Microsoft Azure · AWS · GCP

**Network security:** FortiGate · FortiManager · IPS/IDS · IPsec VPN· Palo Alto · Panorama · Cisco FTD · Cisco ASA · Juniper SRX

**Routing and switching:** BGP · OSPF · IS-IS · MPLS · EVPN · VXLAN · IPv6 · QoS

**Monitoring and ops:** Splunk · SolarWinds · ServiceNow · NetFlow · SNMPv3 · Syslog

**Lab & Validation:** Eve-ng · Containerlab · Wireshark · CML· GNS3


---

## 🎓 Certifications

- CCNP Enterprise
- CCNP Security
- CCNP Automation
- CISSP
- Fortinet NSE 4


## 🚀 Engineering Profile & Highlights

### 🛠️ High-Impact Case Study: Multi-Vendor IPsec Interoperability

### **Palo Alto to Cisco ASA IPsec S2S VPN Phase 2 Mismatch**
* **Context:** Troubleshot a critical Site-to-Site (S2S) IPsec VPN tunnel setup between a local legacy Cisco ASA (IKEv1) and a customer's newly migrated Palo Alto firewall.
* **Problem:** Phase 1 established cleanly, but Phase 2 repeatedly failed on the ASA with `bad proposal received` errors, despite matching encryption, hash, and lifetime parameters across both ends. Disabling Perfect Forward Secrecy (PFS) on both sides did not resolve the mismatch.
* **Root Cause Analysis:** PAN-OS can implicitly include Diffie-Hellman (PFS) exchange payload structures or Quick Mode defaults even when explicitly set to "disabled" in the configuration UI. The legacy Cisco ASA flagged these unexpected payload structures as a proposal mismatch and rejected the negotiation.
* **Resolution:** Explicitly configured and synchronized Perfect Forward Secrecy (PFS) DH groups on both firewalls. Forcing both peers to explicitly negotiate the exact Phase 2 DH exchange parameters resolved the payload disagreement and brought the tunnel fully operational.
* **Key Takeaway:** Vendor interoperability—especially with legacy IKEv1 devices—often requires accounting for implicit platform defaults and underlying Quick Mode payload structures rather than relying solely on UI settings.

## 🤝 Let's connect

Hiring, building, or just want to talk network automation? Say hi.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chijindu-onuoha)

📍 Based in New Zealand



<!--
**chijindu/chijindu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
