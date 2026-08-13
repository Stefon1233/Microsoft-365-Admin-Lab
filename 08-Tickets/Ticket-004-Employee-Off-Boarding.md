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

* Shared mailbox conversion
* Mailbox delegation
* Automatic reply configuration
* License removal
* Deleted/removed user
* Failed former-user sign-in

### Lessons Learned

Practiced a structured employee offboarding workflow that balances security, license management, and organizational data retention.

---