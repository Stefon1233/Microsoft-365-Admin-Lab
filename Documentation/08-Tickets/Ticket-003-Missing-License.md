# Ticket ##
Ticket 003 — Missing License

### Issue

User cannot access licensed Microsoft 365 services.

### User Report

User reported that expected Microsoft 365 applications/services were unavailable.

### Environment

* Microsoft 365 Admin Center
* Microsoft Entra ID
* Microsoft 365 Business Basic

### Symptoms

* User account exists.
* User can authenticate.
* Licensed Microsoft 365 services are unavailable or limited.

### Investigation

* Reviewed the user's account.
* Checked **Licenses and apps**.
* Identified the missing Microsoft 365 Business Basic license.

### Troubleshooting Steps

1. Selected the test user in Microsoft 365 Admin Center.
2. Opened **Licenses and apps**.
3. Removed the Microsoft 365 Business Basic license to reproduce the issue.
4. Saved the changes.
5. Signed in as the affected user.
6. Verified that licensed services were unavailable.
7. Returned to Microsoft 365 Admin Center.
8. Reassigned the Business Basic license.
9. Saved the changes.
10. Verified the license assignment.
11. Signed in as the user again.
12. Verified that Microsoft 365 services were restored.

### Resolution

Microsoft 365 Business Basic was reassigned to the user and licensed services became available again.

### Root Cause

The required Microsoft 365 license was not assigned to the user.

### Skills Used

* Microsoft 365 Licensing
* License Assignment
* User Administration
* Service Troubleshooting
* Microsoft 365 Admin Center

### Screenshot(s)

* User without license
* License assignment screen
* Business Basic assigned
* Restored user services

### Lessons Learned

Learned how Microsoft 365 licensing directly controls service availability and how to diagnose access problems caused by missing licenses.

---