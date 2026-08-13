# Ticket ##
Ticket 004 — Employee Off-Boarding

### Issue

Employee has left the organization and the Microsoft 365 account must be securely off-boarded.

### User Report

Management requested termination of the employee's Microsoft 365 access while preserving required mailbox information.

### Environment

* Microsoft 365 Admin Center
* Exchange Admin Center
* Microsoft Entra ID

### Symptoms

* Employee account remains active.
* Mailbox contains organizational information that needs to be retained.
* Microsoft 365 license is still assigned.

### Investigation

Reviewed the employee's:

* Account status
* Mailbox
* License assignment
* Mailbox access requirements

### Troubleshooting Steps

1. Located the departing employee.
2. Converted the user's mailbox to a shared mailbox.
3. Delegated mailbox access to an appropriate test manager/admin.
4. Configured an automatic reply explaining that the employee was no longer available.
5. Verified mailbox configuration.
6. Released the employee's Microsoft 365 license.
7. Removed/deleted the employee account as planned for the lab.
8. Attempted to authenticate using the former employee account.
9. Verified that sign-in failed.
10. Confirmed required mailbox access remained available to the delegated user.

### Resolution

The employee was successfully off-boarded. Access was removed, the license was released, and required mailbox information was preserved/delegated.

### Root Cause

Normal employee separation/off-boarding request.

### Skills Used

* Employee Offboarding
* Exchange Online
* Shared Mailboxes
* Mailbox Delegation
* Automatic Replies
* Microsoft 365 Licensing
* Identity Lifecycle Management
* Account Security

### Screenshot(s)

* <img width="1440" height="876" alt="Offboarding-Marcus-Reed-Account" src="https://github.com/user-attachments/assets/05e9faff-82f7-4714-9268-867d282d6247" />
* <img width="1440" height="876" alt="Offboarding-Marcus-Reed-Licenses-Removed" src="https://github.com/user-attachments/assets/13350dfb-ad43-4023-969c-7501e92c7235" />
* <img width="1440" height="876" alt="Offboarding-Marcus-Reed-Deleted-Users" src="https://github.com/user-attachments/assets/08f5ff5d-2388-41b3-9a08-340a368057bd" />
* <img width="1440" height="876" alt="Offboarding-Marcus-Reed-Access-Denied" src="https://github.com/user-attachments/assets/06fdf641-490c-4f9e-8713-0528ba89b55f" />


### Lessons Learned

Practiced a structured employee offboarding workflow that balances security, license management, and organizational data retention.

---
