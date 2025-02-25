## Project - Hybrid Infrastructure Consultancy Report

# Hybrid Infrastructure for On-Premises and Cloud
 
**Author**: Umeda Oqilova  
📅 **Date**: Project for On-Premises Computing Course (2024) 

---

## 📂 Project Files
- **To get detailed information about the report with diagrams, cost analysis, and technical recommendations, please READ [consultancy report here (PDF)](Consultancy project - Umeda O..pdf)** 

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
- **Mind Map**: High-level visualization of the hybrid architecture plan.


  <img width="482" alt="Image" src="https://github.com/user-attachments/assets/0d6ab922-a5ae-40f2-9dd0-59cd7b468f3e" />


### **Architecture Overview**:
- **On-Premises**:
  - Dual-location setup with segregated VLANs and replication mechanisms for disaster recovery.
  - **Network Topology**: Packet Tracer simulation showcasing the proposed on-prem infrastructure.


  <img width="552" alt="Image" src="https://github.com/user-attachments/assets/5437d9a7-3d32-4647-84b5-83dce176d889" />

   
- **Cloud Integration**:
  - Utilized Azure ExpressRoute for private connections between customer's on-premises environment and Azure cloud environment.
  - Recommended moving developer workloads and DFS system to Azure for scalability.

---

## 📊 Results

### 💰 Cost Benefits of Moving to Azure
1. Annual savings of **NOK 27,209,049** by moving storage to Azure Files.
**TCO Calculator Results for DFS System** 


      <img width="295" alt="Image" src="https://github.com/user-attachments/assets/ea9db560-ba55-4f43-9c46-28425c60eafe" />  


2.  Developer environment migration savings of **NOK 199,187,778** by utilizing Azure DevTest Labs for dynamic scaling.
**TCO Calculator Results for Developer Environment**


      <img width="283" alt="Image" src="https://github.com/user-attachments/assets/be2e21ef-a9c0-4506-b086-995e7dcdb9f3" /> 


### 🔑 How These Savings Are Achieved:
- **Pay-as-You-Go Model**: Eliminates upfront capital expenses for hardware, replacing them with flexible operational costs that scale with usage.
- **Operational Cost Reduction**: Reduces expenses related to IT maintenance, cooling, electricity, and software licensing.
- **Dynamic Scalability**: Azure DevTest Labs allows seamless scaling of resources during high demand and automatic cost reductions during downtime.

### 🌟 Why It Matters:
- Startups companies benefit from improved budget flexibility and reduced financial risks.
- Azure’s advanced cost management tools, such as tagging for cost allocation, budget tracking, and real-time alerts, ensure resource efficiency and prevent overspending.

By leveraging Azure’s hybrid infrastructure capabilities, critical workloads remain securely on-premises while non-sensitive workloads take full advantage of Azure’s scalability, cost efficiency, and availability. This approach aligns IT infrastructure with business growth objectives, enabling innovation and sustained success.

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

Feel free to reach out on LinkedIn for discussions or collaborations
