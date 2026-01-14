# Risk Assessment (Sample)

This document provides a **sample ISO/IEC 27001 risk assessment**
created for educational and portfolio purposes.

It demonstrates a **basic understanding of risk-based thinking**
as required by ISO/IEC 27001 Clause 6.

⚠️ This is a simulated example and not a real organizational assessment.

---

## 1. Purpose of Risk Assessment

The purpose of a risk assessment is to:
- Identify information security risks
- Analyze how threats can exploit vulnerabilities
- Evaluate the potential impact on the organization
- Decide how risks should be treated

ISO/IEC 27001 requires organizations to **identify and manage risks**
to information assets.

---

## 2. Risk Assessment Approach (Beginner-Friendly)

This sample uses a **simple qualitative approach**:

- **Risk = Threat × Vulnerability × Impact**
- Risk levels are described as **Low, Medium, or High**
- No complex calculations are used

This approach is suitable for small organizations and learning purposes.

---

## 3. Identified Information Assets

The following assets were identified as critical:

| Asset ID | Asset Name | Description |
|--------|-----------|-------------|
| A1 | Employee Laptops | Used for daily work and remote access |
| A2 | Customer Database | Stores customer personal information |
| A3 | Company Email System | Used for internal and external communication |
| A4 | Web Application Server | Hosts company services |

---

## 4. Risk Identification

This section identifies **threats and vulnerabilities**
that could affect the assets.

---

### Risk 1: Unauthorized Access to Employee Laptops

- **Asset:** Employee Laptops
- **Threat:** Stolen or lost device
- **Vulnerability:** Weak or no device encryption
- **Impact:** Exposure of sensitive company data
- **Likelihood:** Medium
- **Impact Level:** High
- **Overall Risk Level:** High

**Explanation:**  
If a laptop is lost and not encrypted, an attacker could access
company data directly.

---

### Risk 2: Phishing Attack on Company Email

- **Asset:** Company Email System
- **Threat:** Phishing emails
- **Vulnerability:** Low employee awareness
- **Impact:** Credential theft or malware infection
- **Likelihood:** High
- **Impact Level:** Medium
- **Overall Risk Level:** High

**Explanation:**  
Phishing relies heavily on human error and is one of the most common
attack methods.

---

### Risk 3: Data Breach in Customer Database

- **Asset:** Customer Database
- **Threat:** External attacker
- **Vulnerability:** Weak access controls
- **Impact:** Loss of customer trust and legal penalties
- **Likelihood:** Medium
- **Impact Level:** High
- **Overall Risk Level:** High

**Explanation:**  
Unauthorized access to customer data could result in serious
reputational and legal damage.

---

### Risk 4: Service Downtime Due to Malware

- **Asset:** Web Application Server
- **Threat:** Malware infection
- **Vulnerability:** Unpatched software
- **Impact:** Service unavailability
- **Likelihood:** Low
- **Impact Level:** Medium
- **Overall Risk Level:** Medium

**Explanation:**  
Outdated software increases the risk of malware exploitation.

---

## 5. Risk Evaluation Summary

| Risk ID | Asset | Risk Level |
|------|-------|------------|
| R1 | Employee Laptops | High |
| R2 | Email System | High |
| R3 | Customer Database | High |
| R4 | Web Application Server | Medium |

High risks require **immediate attention**.

---

## 6. Risk Treatment Options

ISO/IEC 27001 allows four main risk treatment options:

- **Risk Mitigation:** Apply security controls
- **Risk Avoidance:** Stop the risky activity
- **Risk Transfer:** Use insurance or third parties
- **Risk Acceptance:** Accept the risk

---

## 7. Sample Risk Treatment Decisions

| Risk ID | Treatment Option | Reason |
|------|-----------------|--------|
| R1 | Mitigate | Encrypt laptops and enforce device security |
| R2 | Mitigate | Security awareness training |
| R3 | Mitigate | Strengthen access controls |
| R4 | Accept | Low likelihood and manageable impact |

---

## 8. Link to ISO 27001 Controls

Risk treatment decisions will be mapped to **Annex A controls**
in the Statement of Applicability (SoA).

---

## 9. Key Takeaways

- Risk assessment is central to ISO 27001
- Risks are based on assets, threats, and vulnerabilities
- Not all risks are treated the same way
- Documentation is critical

---

## 10. Disclaimer

This risk assessment is a **sample document for learning purposes only**
and does not represent a real organizational risk assessment.
