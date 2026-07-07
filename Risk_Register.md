# Risk Register : Third Wave Coffee Co.

**Last Updated:** 2026-07-07  
**Prepared By:** Aryan Neupane

---

## Scenario Overview

Third Wave Coffee Co. is a single-location coffee shop with eight employees. The business uses a tablet-based Point of Sale (POS) system connected to Wi-Fi to process credit card payments, stores customer loyalty information (name, email, and phone number) in a cloud-based application, and provides free public Wi-Fi to customers using the same router as the POS network. As the newly hired GRC consultant, the objective is to identify the organization's primary security risks before the busy holiday season and recommend appropriate risk treatments and security controls.

---

# Risk Register

| ID | Asset | Threat | Vulnerability | Likelihood | Impact | Risk Rating | Treatment | Recommended Control | Control Type | Control Function |
|----|-------|--------|---------------|------------|--------|-------------|-----------|---------------------|--------------|------------------|
| **R-001** | POS System / Card Payment Data | Cybercriminal compromises the POS system or steals card payment information | Guest Wi-Fi and POS traffic share the same unsegmented network | High | High | **Critical** | Mitigate | Implement network segmentation by placing the POS system on a dedicated VLAN separated from the guest Wi-Fi network | Technical | Preventive |
| **R-002** | Customer Loyalty Database | Unauthorized access resulting in exposure of customer personally identifiable information (PII) | Weak authentication, lack of Multi-Factor Authentication (MFA), and weak password practices | Medium | High | **High** | Mitigate | Enable MFA, enforce a strong password policy, implement Role-Based Access Control (RBAC), and perform periodic access reviews | Technical | Preventive |
| **R-003** | Cash Drawer | Theft or unauthorized access resulting in financial loss | Unlocked cash drawer, inadequate physical security, lack of staff supervision, and absence of cash handling procedures | Medium | Medium | **Medium** | Mitigate | Keep the cash drawer locked when not in use, restrict access to authorized employees, install CCTV, and establish cash handling procedures | Physical / Administrative | Preventive |
| **R-004** | Wi-Fi Network | Unauthorized network access allowing attackers to compromise business systems | Public guest Wi-Fi shares the same router as the business network; default router settings and lack of network segmentation | High | High | **High** | Mitigate | Separate guest Wi-Fi from the business network using VLANs or a dedicated guest network, enable WPA3 (or WPA2-Enterprise), change default credentials, and keep router firmware updated | Technical | Preventive |

---

# Risk Rating Scale

| Likelihood | Description |
|------------|-------------|
| **Low** | Unlikely to occur under normal circumstances |
| **Medium** | Could occur occasionally |
| **High** | Likely to occur or has a high probability |

| Impact | Description |
|---------|-------------|
| **Low** | Minimal operational or financial impact |
| **Medium** | Moderate disruption or financial loss |
| **High** | Significant financial, operational, legal, or reputational impact |

### Overall Risk Rating Matrix

| Likelihood | Impact | Risk Rating |
|------------|--------|-------------|
| Low | Low | Low |
| Low | Medium | Low |
| Medium | Medium | Medium |
| Medium | High | High |
| High | Medium | High |
| High | High | Critical |

---

# Risk Treatment Options

| Treatment | Description |
|-----------|-------------|
| **Accept** | Accept the risk because it falls within the organization's risk tolerance. |
| **Avoid** | Eliminate the activity that creates the risk. |
| **Mitigate** | Reduce the likelihood or impact by implementing security controls. |
| **Transfer** | Shift the financial impact to another party (e.g., insurance or a service provider). |

---

# Conclusion

The assessment identified four primary risks affecting Third Wave Coffee Co. The most critical risk is the lack of network segmentation between the public Wi-Fi and the POS system, which could expose payment processing systems to cyberattacks. Additional high-priority risks include unauthorized access to the customer loyalty database and compromise of the business Wi-Fi network. Implementing preventive technical controls such as network segmentation, Multi-Factor Authentication (MFA), Role-Based Access Control (RBAC), secure Wi-Fi configuration, and physical controls for cash handling will significantly reduce the organization's overall cybersecurity risk and improve its security posture before the holiday season.