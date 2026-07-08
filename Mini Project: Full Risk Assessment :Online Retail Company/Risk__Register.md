# Risk Register : NorthPeak Outfitters



| Risk ID | Description | Category | Inherent L | Inherent I | Inherent Rating | Existing Controls | Residual Rating | Owner | Treatment | Target Date | Status | Next Review |
|---------|-------------|----------|------------|------------|------------------|-------------------|-----------------|-------|-----------|--------------|--------|--------------|
| R-001 | Unauthorized access to the Shopify Admin Panel through credential stuffing due to lack of MFA. | Cybersecurity | Likely | Major | High | Password policy and account monitoring | Medium | IT Manager | Mitigate (Enforce MFA and monitor login attempts) | 2026-08-01 | Open | 2026-09-01 |
| R-002 | Customer data exposure caused by a breach of the cloud-hosted customer and order database. | Data Security | Possible | Severe | High | Cloud access controls, encrypted storage, regular backups | Medium | IT Manager | Mitigate (Strengthen access control and continuous monitoring) | 2026-08-15 | Open | 2026-09-15 |
| R-003 | Payment service disruption or compromise due to a third-party payment gateway outage or breach during Black Friday. | Third-Party Risk | Possible | Major | High | PCI DSS-compliant payment provider and service agreement | Medium | Finance Manager | Transfer (Rely on vendor security controls and SLA) | 2026-08-10 | Open | 2026-09-10 |
| R-004 | Phishing attack compromises employee accounts through the email marketing platform or corporate email. | Human Risk | Likely | Moderate | High | Security awareness training and email spam filtering | Medium | HR Manager | Mitigate (Conduct phishing simulations and enable MFA) | 2026-08-05 | Open | 2026-09-05 |
| R-005 | Malware infection or unauthorized access through remote employees' personal laptops without endpoint protection. | Endpoint Security | Likely | Major | High | Antivirus software and VPN access | Medium | IT Manager | Mitigate (Deploy endpoint protection and enforce BYOD policy) | 2026-08-20 | Open | 2026-09-20 |

## Scales

**Likelihood:** Rare / Unlikely / Possible / Likely / Almost Certain

**Impact:** Negligible / Minor / Moderate / Major / Severe

**Rating:** Low / Medium / High / Critical