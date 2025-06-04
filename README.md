should this be in my readme? # IAM Project: Active Directory on Windows Server Core

## Overview
This project demonstrates the deployment and management of an Active Directory (AD) environment using Windows Server Core. The focus is on foundational Identity and Access Management (IAM) tasks including Organizational Unit (OU) creation, user management with least privilege access, and implementation of password and account lockout policies through Group Policy Objects (GPOs).

## Objectives
- Deploy and configure Windows Server Core as an Active Directory domain controller.
- Create and organize OUs to structure users and resources effectively.
- Manage domain users with least privilege principles to minimize access rights.
- Implement robust password policies enforcing minimum length, complexity, and history.
- Configure account lockout policies to protect against brute-force attacks.
- Apply Group Policy Objects to enforce security best practices.
- Use PowerShell and sconfig for automation and management.
- Plan for future integration with third-party identity providers such as Okta.

## Environment Setup
- Windows Server Core 2019/2022
- Active Directory Domain Services (AD DS)
- Virtualization platform: VirtualBox / Hyper-V
- Windows 10/11 clients for domain joining and testing

## Key Steps & Features
1. Installed and configured Windows Server Core using the sconfig tool for streamlined setup.
2. Promoted the server to a domain controller, enabling DNS services.
3. Created Organizational Units (OUs) such as HR and IT to segregate users and apply least privilege access.
4. Added and managed domain users, assigning them to their respective OUs with minimal permissions necessary.
5. Configured password policies enforcing minimum length, complexity, and history to enhance security.
6. Set account lockout policies defining lockout duration, threshold, and reset time.
7. Applied Group Policy Objects (GPOs) to ensure enforcement of password and lockout policies as well as least privilege access.
8. Automated user and OU management using PowerShell scripts.
9. Planned integration with Okta for federated authentication (not yet implemented).

## Sample PowerShell Scripts
- User creation with specified OU assignment and restricted permissions.
- OU creation and permission delegation to support least privilege.
- Policy enforcement via Group Policy cmdlets.

## Lessons Learned
- Benefits of Server Core for security and efficient resource utilization.
- Challenges and best practices in managing Active Directory using PowerShell and command-line tools.
- Critical importance of least privilege access in reducing security risks.
- Designing and enforcing strong password and account lockout policies.
- Planning for future integration with cloud identity providers.

## Future Enhancements
- Implement Okta or Azure AD integration for identity federation.
- Automate user provisioning and deprovisioning workflows.
- Enhance security monitoring with event forwarding and SIEM integration.

---

*This project was developed as part of practical training in Identity and Access Management, demonstrating essential Active Directory administration skills relevant for help desk and system administration roles.*
