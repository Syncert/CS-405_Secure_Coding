# 🛡️ Secure Coding Portfolio: Green Pace Security Standards

## 🚀 Project Overview
Welcome to my **Secure Coding Portfolio**, a culmination of best practices, coding standards, and security principles developed through my coursework in CS-405. This repository showcases my approach to **secure software development**, including **risk assessment, encryption policies, and automation within the DevSecOps pipeline**.

As security threats evolve, developers must adopt a **security-first mindset** to ensure that vulnerabilities are mitigated **before they become deeply embedded** in the system. This portfolio encapsulates **Zero Trust principles**, **defense-in-depth methodologies**, and **automated security policies** for **building resilient applications**.

---

## 🔒 Core Security Principles
This project aligns with **10 core security principles** to reinforce best practices in **secure software development**:

1. **Validate Input Data** – Prevent SQL injections, buffer overflows, and logic errors.
2. **Heed Compiler Warnings** – Treat warnings as potential security vulnerabilities.
3. **Architect for Security** – Implement security in the **design phase**, not as an afterthought.
4. **Keep It Simple** – Reduce complexity to minimize attack surfaces.
5. **Default Deny** – Restrict all actions **unless explicitly allowed**.
6. **Least Privilege** – Grant the **minimum access** required.
7. **Sanitize Data Sent to Other Systems** – Prevent injection attacks and **data leaks**.
8. **Defense in Depth** – Apply **multiple layers** of security.
9. **Use Effective QA Techniques** – Implement **fuzz testing, static analysis, and SAST tools**.
10. **Adopt a Secure Coding Standard** – Follow **OWASP, NIST, and ISO/IEC 27001**.

---

## 🖥️ Secure Coding Standards (C/C++)

This portfolio includes **10 secure coding standards** for **C/C++ development**, ensuring that vulnerabilities are addressed **before deployment**. Each standard includes:
✔️ **Compliant Code**  
❌ **Non-Compliant Code**  
🛠️ **Automated Detection Tools**

### 🔹 Key Coding Standards
- **[STD-001-CPP] Proper Use of Data Types** – Prevents undefined behavior and overflow issues.
- **[STD-002-CPP] Validate Data Range** – Ensures variables remain within expected constraints.
- **[STD-003-CPP] String Correctness** – Avoids buffer overflows and improper null termination.
- **[STD-004-CPP] SQL Injection Prevention** – Implements parameterized queries to block attacks.
- **[STD-005-CPP] Memory Protection** – Prevents **dangling pointers, leaks, and buffer overflows**.
- **[STD-006-CPP] Assertions** – Uses runtime checks instead of assertions for validation.
- **[STD-007-CPP] Exception Handling** – Catches **specific exceptions** for better debugging.
- **[STD-008-CPP] Secure Logging** – Avoids logging **sensitive information** (PII, passwords).
- **[STD-009-CPP] Input Validation** – Restricts **dangerous input** that could cause crashes.
- **[STD-010-CPP] Code Documentation** – Ensures readability and maintainability.

🔍 *Automated security checks use tools like:*  
- **Clang-Tidy** (Static Analysis)  
- **SonarQube** (Code Scanning)  
- **Cppcheck** (Memory Leaks)  
- **SQLMap** (SQL Injection Detection)  
- **Valgrind** (Memory Profiling)  

---

## 🛡️ Risk Assessment & Threat Modeling

Security implementation requires a **balance between risk and cost**. This project employs **structured risk assessment frameworks** like **FAIR, NIST, and OWASP** to **prioritize security measures**. 

### 🎯 Threat Categorization:
| Risk Level | Likelihood | Impact |
|------------|-----------|--------|
| **Critical** | Very Likely | System failure or data breach |
| **High** | Likely | Major security risk, requiring mitigation |
| **Medium** | Moderate | Functional issues with potential security concerns |
| **Low** | Unlikely | Inefficiencies, but no direct security impact |

---

## 🔐 Encryption & Authentication Policies

### **🔑 Encryption Strategies**
1. **Data at Rest** – AES-256 encryption for storage and databases.
2. **Data in Transit** – TLS 1.3, SSH, and VPN protocols for secure communication.
3. **Data in Use** – **Secure enclaves, homomorphic encryption, and RAM protection**.

### **🔑 AAA Security Model (Authentication, Authorization, Accounting)**
✔️ **Multi-Factor Authentication (MFA)** for user identity verification.  
✔️ **Role-Based Access Control (RBAC)** with **least privilege enforcement**.  
✔️ **SIEM logging** for real-time **security event monitoring**.

---

## 🤖 DevSecOps: Automation & CI/CD Integration

To **enforce security policies**, this project integrates **automated security tools** into the **DevSecOps pipeline**. 

### **🔹 Security Automation Stack**
- **Static Application Security Testing (SAST)** – Detects vulnerabilities in source code.
- **Dynamic Application Security Testing (DAST)** – Scans running applications.
- **Infrastructure-as-Code (IaC) Security** – Automates **cloud and network security checks**.
- **SIEM & Log Monitoring** – Provides **real-time attack detection**.

### **🔹 Unit Testing for Security**
📌 **Testing [STD-009-CPP] – Input Validation**  
- ✅ Accepts valid input  
- ❌ Rejects **SQL injections, buffer overflows, and null values**  

---

## 🎓 Key Takeaways from CS-405

### **💡 Lessons Learned**
- **Security must be integrated from the start** – Shift-left security minimizes vulnerabilities.  
- **Zero Trust is essential** – **Always verify, never trust** users, devices, and services.  
- **Automated security testing is a necessity** – Tools like **SonarQube, OWASP ZAP, and SIEM monitoring** streamline risk mitigation.  
- **Risk assessment is critical** – Not all threats require equal investment; focus on **high-impact vulnerabilities**.  
- **A security culture matters** – Security isn’t just a technical issue—it’s a mindset that needs to be **embedded in development workflows**.  

---

## 📂 Repository Structure

