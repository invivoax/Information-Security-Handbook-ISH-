Table of Contents

- [Company Permissions Policy](#permissions-policy)
- [Security Scan Schedule](#security-scan-schedule)
- [Access Request Form](#access-request-form)

# **Company Permissions Policy**

### Purpose

---

The purpose of this sections is to outline the permissions and access controls in place within Invivo AX to ensure secure handling of sensitive information.

### Scope

---

This policy applies to all employees, contractors, and third-party vendors who have access to company systems, networks, or data.

### Permissions Hierarchy

---

| Permission Level | Description                                                            |
| ---------------- | ---------------------------------------------------------------------- |
| **Owner**        | High-level executives and management with full access rights.          |
| **Manager**      | Department managers who oversee employees within their team.           |
| **Employee**     | Regular staff members with limited access to company systems and data. |

### Access Control Procedures

---

- Access Standards: All access rights and permissions will follow our Least Privilege Model, where employees and contractors are granted only the necessary permissions to perform their job functions.
- Initial Access: Employees and contractors are granted initial access to company services and accounts through our standardized onboarding checklist.
- Access Requests: Employees can request additional permissions or access rights by submitting a formal request form (see end).
- Revocation of Permissions: Invivo AX regularly audits permissions and their usage. Permissions will be immediately revoked upon employee separation or role change, as well as when permissions are no longer needed or used.

### Data Classification

---

| Category              | Description                                                                           |
| --------------------- | ------------------------------------------------------------------------------------- |
| **Confidential**      | Highly sensitive information, such as financial data and personal identifiable info.  |
| **Internal Use Only** | Company-wide information not intended for external sharing (e.g., internal policies). |

# Security Scan Schedule

## Purpose:

The purpose of this section is to outline the scheduled frequency and scope of security scans performed on our network, systems, and applications.

## Scope:

- **Network Scans**: Regularly scheduled scans of all company networks, including perimeter firewalls, internal subnets, and DMZs.
- **System Scans**: Scheduled scans of critical servers, workstations, and other devices to identify vulnerabilities and ensure compliance with security policies.
- **Application Scans**: Regular scans of web applications, APIs, and other software systems to detect potential security risks.

## Scan Schedule:

| Scan Type        | Frequency                                                         |
| ---------------- | ----------------------------------------------------------------- |
| Network Scan     | continues monitoring through VPN tooling                          |
| System Scan      | NA                                                                |
| Application Scan | Every update and deploy of the application (frontend and backend) |

## Scan Details:

- **Vulnerability Assessment**:

| Vulnerability          | Type Priority Level                        |
| ---------------------- | ------------------------------------------ |
| Critical (CVSS 9-10)   | High - Remediation within 72 hours or less |
| Important (CVSS 7-8.9) | Medium - Remediation within 1 week or less |
| Moderate (CVSS 4-6.9)  | Low - Remediation within 2 weeks or less   |

## Reporting:

- **Scan Results**:

  - Report Frequency: Weekly email summaries, Monthly detailed report, Quarterly summary
  - Reporting Format: Email (weekly), PDF/Excel spreadsheet (monthly and quarterly)
  - Recipients: CTO, CEO, Senior Management

- **Incident Response**:

  - Procedures:
    - Initial Response (0-1 hour):
      - Identify and contain the affected area/system
      - Notify relevant stakeholders (e.g., management, IT team)
      - Activate emergency response procedures (if applicable)
    - Investigation (1-24 hours):
      - Gather evidence and conduct a thorough investigation
      - Determine root cause and scope of incident
      - Identify affected systems/data/users
    - Containment and Eradication:
      - Implement containment measures to prevent further damage
      - Develop and execute eradication plans (e.g., patching, system updates)
    - Recovery and Post-Incident Activities:
      - Restore normal operations as soon as possible
      - Conduct post-incident review and analysis
      - Update incident response plan based on lessons learned

## Review and Revision Schedule:

- **Schedule Review**: This security protocol document shall be reviewed and updated at least every 6 months or as needed to ensure it remains relevant and effective.

  - Quarterly reviews: Will conduct quarterly reviews with the CTO to discuss any changes in company policies, procedures, or technology that may impact this document.
  - Annual review: A comprehensive annual review of this document shall be conducted, involving input from all stakeholders. This review will include:
    - Reviewing incident response and remediation processes
    - Updating vulnerability management and patching schedules
    - Ensuring compliance with relevant laws, regulations, and industry standards

## Revision Process:

- **Proposal**: Any proposed changes to this document shall be submitted in writing by the DevSecOps Engineer.
- **Review and Approval**: The CTO will review all proposals for accuracy, completeness, and relevance. If approved, the revised document will be updated accordingly.

---

# Access Request Form

Send to `li-smith@invivoax.com`
Subject: Access Request

### Employee Information

---

- Employee Name: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
- Job Title: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### Requested Access Details

---

- System/Network/Application: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
- Type of access requested (e.g., read-only, edit): \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
- Reason for requesting access: \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

### Additional Information or comments

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
