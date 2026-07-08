# Risk Assessment Report: NorthPeak Outfitters

**Date:** 2026-07-08  
**Assessor:** Aryan Neupane  
**Scope:** NorthPeak Outfitters' e-commerce platform, customer data, payment processing, remote workforce, and warehouse network.

---

## 1. Executive Summary

A qualitative risk assessment was conducted to identify and evaluate cybersecurity risks affecting NorthPeak Outfitters before the Black Friday sales period. The assessment found five high-priority risks related to unauthorized access, customer data exposure, phishing attacks, third-party payment services, and insecure remote employee devices. Implementing stronger authentication, endpoint security, employee awareness training, and improved network security will significantly reduce the organization's overall risk.

---

## 2. Scope and Methodology

- **Scope:** Shopify storefront, Shopify Admin Panel, customer product and order database, payment gateway integration, email marketing platform, and remote employee laptops.
- **Method:** Qualitative 5×5 Risk Matrix.
- **Data Sources:** Business scenario documentation, asset inventory, threat identification, vulnerability analysis, and industry best practices.

---

## 3. Key Findings

| Risk ID | Description | Rating | Recommended Action |
|---------|-------------|--------|--------------------|
| R-001 | Unauthorized access to the Shopify Admin Panel through credential stuffing due to lack of MFA. | High | Enforce Multi-Factor Authentication (MFA), implement account lockout policies, and monitor login attempts. |
| R-002 | Customer data exposure caused by a breach of the cloud-hosted customer and order database. | High | Strengthen access controls, encrypt sensitive data, and enable continuous monitoring. |
| R-003 | Payment processing disruption or compromise due to a third-party payment gateway outage or breach. | High | Monitor vendor security, review Service Level Agreements (SLAs), and maintain an incident response plan. |
| R-004 | Employee accounts compromised through phishing attacks targeting remote staff. | High | Conduct regular security awareness training, phishing simulations, and enforce MFA. |
| R-005 | Malware infection or unauthorized access through employees' personal laptops used for remote work. | High | Deploy endpoint protection, enforce a BYOD security policy, and require VPN access. |

---

## 4. Risk Summary by Category

- **Critical:** 0
- **High:** 5
- **Medium:** 0
- **Low:** 0

---

## 5. Recommendations

1. **IT Manager** should enforce Multi-Factor Authentication (MFA) for all administrative accounts by **2026-08-01**.
2. **IT Manager** should strengthen cloud database security by implementing encryption, least-privilege access, and continuous monitoring by **2026-08-15**.
3. **Finance Manager** should review the third-party payment provider's security controls and Service Level Agreement before the Black Friday sales period by **2026-08-10**.
4. **HR Manager** should conduct mandatory phishing awareness training and simulated phishing exercises for all employees by **2026-08-05**.
5. **IT Manager** should implement endpoint protection, VPN enforcement, and a formal Bring Your Own Device (BYOD) policy for remote employees by **2026-08-20**.

---

## 6. Appendix

The complete Risk Register and Asset Inventory are attached separately as supporting documentation.