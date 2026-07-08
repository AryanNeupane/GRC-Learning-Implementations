# Access Control Policy : Third Wave Coffee Co.


---

# 1. Policy Statement

Third Wave Coffee Co. is committed to protecting its business systems, payment information, customer data, and other sensitive information from unauthorized access.

All access to company systems, applications, and data must be:
- Authorized by management.
- Authenticated using secure credentials.
- Restricted according to the **Principle of Least Privilege**, ensuring employees have access only to the information and systems necessary to perform their job responsibilities.

Customer information, including names, email addresses, and phone numbers, must be handled securely and protected against unauthorized disclosure, alteration, or loss.

---

# 2. Access Control Standards

### Authentication
- Passwords must contain **at least 14 characters**.
- Passwords must include a combination of uppercase letters, lowercase letters, numbers, and special characters.
- Multi-Factor Authentication (MFA) is required for:
  - Cloud applications
  - Remote access
  - Administrative accounts

### Account Management
- Every employee must have an individual user account.
- Shared user accounts are prohibited.
- **Principle of Least Privilege** should be implemented

### Network Security
- The business Wi-Fi and POS network must remain separated through network segmentation.
- Default router usernames and passwords must be changed before deployment.
- Router firmware and networking equipment must be updated at least every **6 months**, or sooner if critical security patches are released.
- Wi-Fi passwords must be changed every **90 days**, or immediately following suspected compromise or employee departure.

---

# 3. Access Provisioning Procedure (New Employee)

When onboarding a new employee:

1. The store manager submits an access request based on the employee's job responsibilities.

2. An individual account is created using Role-Based Access Control (RBAC).
3. Employees are granted only the minimum permissions required to perform their duties.
4. Administrative privileges are not granted unless specifically approved.
5. MFA is enabled before access is provided to cloud applications.


### Employee Offboarding

When an employee leaves the company:

1. Disable all user accounts immediately.
2. Revoke access to cloud services and business applications.
3. Change shared passwords if applicable.
4. Collect company-owned devices, keys, or access cards.
5. Document completion of the offboarding process.

---

# 4. Security Guidelines

Employees are expected to:

- Use a password manager to generate and securely store strong passwords.
- Never share passwords or MFA codes with anyone.
- Never disclose company-sensitive information to unauthorized individuals.
- Lock devices whenever they are left unattended.
- Report any suspected phishing attempts, lost devices, or suspicious activities immediately.


