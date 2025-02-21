# 🌍 Proven National Worker (PNW) - MVP Payroll System

### **🚀 Overview**
This is the **Minimum Viable Product (MVP)** for the **PNW Payroll System**, integrating **Aleo & Aztec smart contracts** for **secure, private, and compliant payroll processing**.

### **📜 Included Contracts**
#### **🔹 Aleo Contracts**
- **Payroll Processing**
  - `pncw_payroll.leo` → PNcW (Citizen Workers) payroll
  - `pniw_payroll.leo` → PNiW (Immigrant Workers) payroll
- **Governance & Compliance**
  - `employer_agreement.leo` → Employer compliance enforcement
  - `process_tax_compliance.leo` → Employer tax processing
  - `compliance_tracking.leo` → Certification & worker compliance
  - `subdao_governance.leo` → Worker-led payroll governance
- **Fund Management**
  - `subdao_aleo_usdc_reserve.leo` → Payroll fund reserve
  - `oversightdao_combined_reserve.leo` → Emergency payroll reserves

#### **🔹 Aztec Contracts**
- `aztec_payroll.noir` → Private payroll execution on Aztec
- `subdao_circle_usdc_reserve.noir` → SubDAO-controlled Circle USDC reserve

---

### **🛠 Deployment Guide**
#### **🔹 Using Shell Script (`deploy.sh`)**
```sh
chmod +x deploy.sh
./deploy.sh
