## Project - Hybrid Infrastructure Consultancy Report

# Hybrid Infrastructure for On-Premises and Cloud
 
**Author**: Umeda Oqilova  
📅 **Date**: Semester Project for On-Premises Computing Course (2024)  

---

## 📘 Overview

This project provides a consultancy report for the merger of two companies, recommending a **Hybrid Infrastructure** to meet their unique operational, security and compliance needs. The proposed solution balances **On-Premises** and **Cloud (Azure)** infrastructure to optimize cost, scalability, security, and efficiency.

---

## 📝 Key Highlights

### **Objective**:
- Evaluate the current infrastructure of two merging companies.
- Provide recommendations for integrating On-Prem and Cloud solutions.
- Address cost-effectiveness, scalability, and security concerns.

### **Proposed Solution**:
- Adopt a **Hybrid Infrastructure**:
  - Retain sensitive data on-premises for compliance and ownership.
  - Migrate less critical workloads to Azure for scalability and cost efficiency.
- Tools and technologies included:
  - **On-Prem**: VLAN, ACL, DHCP, NAT, Storage Replica, Active Directory.
  - **Cloud**: Azure DevTest Labs, Azure TCO Calculator, Azure Files, Role-Based Access Control (RBAC).

### **Outcomes**:
- Improved **data security** and **compliance** for sensitive workloads.
- Reduced operational costs with **Azure's pay-as-you-go model**.
- Enhanced scalability for developer environments and public-facing resources.

---

## 🛠️ Technical Details

### **Technologies Used**:
- **On-Prem Tools**: Packet Tracer, Windows Server, VLANs, NAT, DNS, ACLs.
- **Cloud Tools**: Azure DevTest Labs, Azure Files, RBAC, Azure TCO Calculator.

### **Architecture Overview**:
- **On-Premises**:
  - Dual-location setup with segregated VLANs and replication mechanisms for disaster recovery.
  - Security enhanced via least privilege access and zero-trust principles.
- **Cloud Integration**:
  - Utilized Azure ExpressRoute for private connections between on-premises and cloud environments.
  - Recommended moving developer workloads and DFS system to Azure for scalability.

---

## 📊 Results

### **Cost Savings**:
- Annual savings of **27M NOK** for DFS workloads.
- Developer environment migration savings of **199M NOK** (based on Azure TCO Calculator).

### **Scalability**:
- Dynamic scaling for development and testing workloads using Azure DevTest Labs.

### **Security**:
- Zero-trust model enforced with VLANs, ACLs, and Azure RBAC.

---

## 📂 Project Files

- **[Consultancy Report (PDF)](FILE address)**: Detailed project report with diagrams, cost analysis, and technical recommendations.
- **Mind Map**: High-level visualization of the hybrid architecture plan.
- **Network Topology**: Packet Tracer simulation showcasing the proposed on-prem infrastructure.

---

## 🌐 How to Use This Repository

1. **Explore the PDF**: Review the `Consultancy Report` for an in-depth understanding of the hybrid solution.
2. **Network Design**: Use the Packet Tracer file to simulate and test the proposed topology.
3. **Cost Analysis**: Refer to the Azure TCO calculations in the report to assess financial benefits.

---

## 🚀 Future Scope

- Implement a fully automated cloud cost management system using Azure Cost Management.
- Expand hybrid architecture to support multi-cloud environments.

---

## 🤝 Acknowledgments

- **Noroff School of Technology & Digital Media** for academic support.
- References and tools from Microsoft Learn, Packet Tracer, and Azure documentation.

---

## 📬 Contact

Feel free to reach out for discussions or collaborations
