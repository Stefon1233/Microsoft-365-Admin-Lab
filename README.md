# Microsoft 365 Administration Lab

## Overview

This project documents a hands-on Microsoft 365 administration lab designed to simulate common tasks performed by Help Desk, IT Support, and Microsoft 365 administrators.

The lab demonstrates practical experience with Microsoft Entra ID, Exchange Online, Microsoft Teams, SharePoint Online, user and group administration, licensing, identity security, and common help-desk scenarios.

---

## Network & Services Diagram

<img width="1536" height="1024" alt="Microsoft-365-Admin-Network- -Services-Diagram" src="https://github.com/user-attachments/assets/30a54c07-1118-46dc-8790-09192a575e11" />

---

## Tasks Completed

During this lab, I configured and administered a simulated Microsoft 365 business environment.

### User & Identity Management

* Created and managed 10+ Microsoft 365 user accounts
* Configured user profiles, departments, job titles, and account information
* Reset user passwords and required password changes at next sign-in
* Blocked and restored user sign-in access
* Deleted and restored user accounts
* Managed Microsoft Entra ID users and groups
* Assigned and removed administrative roles
* Reviewed authentication and MFA settings

### Groups & Access Management

* Created Microsoft 365 groups
* Created security groups for department-based access
* Added and removed group members
* Configured group owners and members
* Created and managed distribution lists
* Demonstrated different levels of user access

### License Management

* Assigned Microsoft 365 licenses to users
* Removed licenses to simulate licensing problems
* Troubleshot users with missing licenses
* Reassigned licenses and verified restoration of Microsoft 365 services

### Exchange Online

* Administered Exchange Online through the Exchange Admin Center
* Created a Management shared mailbox
* Configured shared mailbox membership and permissions
* Configured Send As and mailbox delegation permissions
* Created distribution lists
* Configured automatic replies
* Practiced mailbox administration as part of employee offboarding

### Microsoft Teams

* Created multiple department Teams
* Added owners and members
* Created standard channels
* Created a private channel
* Configured department-specific collaboration spaces
* Demonstrated differences in access based on Team membership

### SharePoint Online

* Created multiple SharePoint sites
* Configured site owners, members, and visitors
* Uploaded and managed documents
* Configured different permission levels
* Demonstrated department-based access restrictions
* Tested access using users with different permissions
* Demonstrated SharePoint document version history
* Viewed previous document versions and practiced version restoration

### Employee Lifecycle Administration

* Practiced employee onboarding and account configuration
* Blocked access during simulated employee termination
* Converted an employee mailbox to a shared mailbox
* Delegated mailbox access
* Configured an automatic reply
* Released the Microsoft 365 license
* Deleted the employee account
* Verified that the former employee could no longer sign in

---

# Help Desk Scenarios

## Ticket 001 — Password Reset

**Issue:**
A user was unable to authenticate and required a password reset.

**Troubleshooting & Resolution:**

1. Located the user in the Microsoft 365 Admin Center.
2. Reset the user's password.
3. Required the user to change the temporary password at next sign-in.
4. Verified that the account was available for authentication.

**Result:**
Password reset completed successfully.

**Skills Demonstrated:**
User Administration • Password Management • Microsoft 365 Admin Center

---

## Ticket 002 — Blocked Account

**Issue:**
A user was unable to access Microsoft 365 because sign-in was blocked.

**Troubleshooting & Resolution:**

1. Reviewed the user's account status.
2. Confirmed that sign-in was blocked.
3. Tested the failed authentication scenario.
4. Restored sign-in access.
5. Verified that the account could authenticate again.

**Result:**
User access was successfully restored.

**Skills Demonstrated:**
Microsoft Entra ID • Identity Troubleshooting • Account Access Management

---

## Ticket 003 — Missing Microsoft 365 License

**Issue:**
A user could not access licensed Microsoft 365 services.

**Troubleshooting & Resolution:**

1. Reviewed the user's account and license status.
2. Identified the missing Microsoft 365 license.
3. Reassigned the appropriate license.
4. Verified the user's licensing configuration after the change.

**Result:**
The user's Microsoft 365 license was successfully restored.

**Skills Demonstrated:**
License Management • Microsoft 365 Troubleshooting • User Administration

---

## Ticket 004 — Employee Offboarding

**Issue:**
An employee was leaving the organization and required secure account offboarding.

**Resolution:**

1. Blocked the employee's sign-in.
2. Reset the account password.
3. Converted the mailbox to a shared mailbox.
4. Delegated mailbox access to an appropriate user.
5. Configured an automatic reply.
6. Removed the Microsoft 365 license.
7. Deleted the employee account.
8. Verified that the former employee could no longer authenticate.

**Result:**
The employee was successfully offboarded while appropriate mailbox access was retained.

**Skills Demonstrated:**
Employee Lifecycle Management • Exchange Online • Identity Security • License Management

---

## Ticket 005 — Administrator Access

**Issue:**
A user temporarily required administrative permissions.

**Resolution:**

1. Located the user in Microsoft Entra ID.
2. Assigned the User Administrator role.
3. Verified the role assignment.
4. Removed the administrative role after testing.
5. Verified that elevated access had been removed.

**Result:**
Administrative privileges were successfully granted and subsequently revoked.

**Skills Demonstrated:**
Microsoft Entra Roles • RBAC • Least Privilege • Administrative Access Management

---

# What I Learned

This lab gave me hands-on experience administering a Microsoft 365 environment from both an administrator and end-user perspective. I learned how Microsoft Entra ID, Exchange Online, Microsoft Teams, SharePoint Online, and the Microsoft 365 Admin Center work together to support users across an organization.

One of the most important lessons was understanding the relationship between **identity, licensing, permissions, and service access**. A user account existing in Microsoft 365 does not automatically mean that the user has access to every service. Licenses, group membership, roles, mailbox permissions, Teams membership, and SharePoint permissions can all affect what a user is able to access.

I also gained experience with the **user lifecycle**, including creating accounts, configuring users, resetting passwords, assigning licenses, modifying access, and securely offboarding users. The offboarding scenario was particularly useful because it combined several administrative responsibilities, including blocking authentication, preserving mailbox data, delegating access, configuring automatic replies, releasing licenses, and removing the account.

Working with **Exchange Online** helped me understand the differences between individual mailboxes, shared mailboxes, and distribution lists. I also practiced mailbox delegation and automatic reply configuration.

Through **Microsoft Teams and SharePoint Online**, I learned how groups and permissions affect collaboration. Testing SharePoint with users who had different access levels demonstrated why proper permissions and group membership are important for protecting department-specific information.

The troubleshooting scenarios reinforced a structured help-desk approach:

**Identify the issue → Investigate the configuration → Determine the cause → Implement a solution → Verify the resolution**

Overall, this project improved my confidence navigating Microsoft 365 administration tools and gave me practical experience with many of the tasks performed in Help Desk, IT Support, and junior Microsoft 365 administration roles.

---

# Skills Demonstrated

`Microsoft 365 Administration` • `Microsoft Entra ID` • `Exchange Online` • `Microsoft Teams` • `SharePoint Online` • `User & Group Management` • `Identity and Access Management` • `License Management` • `MFA` • `RBAC` • `Shared Mailboxes` • `Distribution Lists` • `Employee Onboarding & Offboarding` • `Help Desk Troubleshooting` • `Technical Documentation`

