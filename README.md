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


Class 003 — Privileged Identity and Access Security

Date: 20 November 2026
Track: Microsoft 365 & Azure Security
Status: Conceptual lesson and assessment completed

1. Topics Covered

- Principle of Least Privilege (PoLP)
- Separation of duties
- Just-in-Time (JIT) access
- Microsoft Entra Privileged Identity Management (PIM)
- Emergency access accounts
- Privileged account compromise

2. Practical Scenario

Reviewed a fictional organisation where an attacker compromises an administrator account and attempts to gain further privileges.

Security decisions:

- Assign role-specific permissions instead of Global Administrator access.
- Use time-limited privileged access for administrative tasks.
- Maintain two independently protected emergency access accounts.
- Monitor privileged account activity.

3. Security Analysis

An ordinary compromised employee account can still cause damage through:

- Social engineering and impersonation.
- Business email compromise.
- Abuse of existing file and application permissions.
- Misuse of delegated administrative privileges, where assigned.

A compromised account does not automatically have permission to administer the entire tenant. Its effective privileges depend on its assigned roles and access scope.

4. Key Takeaways

- Administrative privileges should be limited and time-bound.
- PIM supports controlled activation of eligible roles.
- Emergency access accounts provide resilience against administrative lockout.
- Human trust and social engineering remain significant security risks.

5. Assessment

Score: 3.5/4

Demonstrated understanding of least privilege, JIT access, emergency account redundancy and social engineering.

Practical status: No live tenant configuration or PIM activation performed.

6. Next Class

Class 004 — Conditional Access and Identity-Based Security
