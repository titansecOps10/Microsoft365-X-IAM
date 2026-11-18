Class 001 — Microsoft 365 Enterprise Architecture 

Date: 17 November 2026
Track: Microsoft 365 & Azure Security
Status: Foundation completed

1. Topics Covered Microsoft 365 overview and core services Microsoft 365 vs Microsoft Azure Tenant architecture Microsoft Entra ID Authentication vs authorisation User Principal Name (UPN) Role-Based Access Control (RBAC) Principle of Least Privilege 2. Practical Scenario 

Designed a conceptual security baseline for a simulated 25-person logistics company in Benin City.

Key concerns:

Shared administrator credentials No Multi-Factor Authentication Uncontrolled user access 3. Security Takeaways Enforce individual user accounts and MFA. Apply least privilege through appropriate roles. Separate administrative and everyday accounts. Establish visibility through identity and audit logs. 4. Practical Status 

Conceptual learning completed. Tenant configuration and hands-on validation are pending.

5. Next Class 

Class 002 — Microsoft 365 Tenant Setup and Administration


Class 002 — Microsoft 365 Tenant Setup and Administration

Date: 18 November 2026
Track: Microsoft 365 & Azure Security
Status: Foundation completed; practical configuration pending

1. Topics Covered

- Microsoft 365 tenant structure
- Domains, users, groups and licences
- Global Administrator privileges
- Identity and access planning
- Security policy testing

2. Practical Scenario

Designed a conceptual security baseline for a 25-person logistics company in Benin City.

Identified weaknesses:

- Shared administrator credentials
- No Multi-Factor Authentication (MFA)
- Uncontrolled guest access
- Poor accountability for administrative actions

3. Security Decisions

- Maintain two independently protected emergency access accounts.
- Require MFA for users.
- Restrict and review guest access.
- Use individual administrator accounts to improve accountability.

4. Key Takeaways

- Shared credentials make it difficult to attribute actions to individuals.
- Excessive administrative privileges increase security risk.
- Emergency access accounts help prevent administrative lockout.
- Access should be restricted according to business needs.

5. Practical Status

Conceptual scenario and knowledge assessment completed. No live tenant configuration or policy testing performed.

6. Next Class

Class 003 — Privileged Identity and Access Security

Focus: reducing the risk and impact of compromised administrator accounts.
