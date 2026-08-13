# Ticket ##
Ticket 002 — Blocked Account

### Issue

User cannot sign in because account sign-in is blocked.

### User Report

User reported being unable to access their Microsoft 365 account despite entering the expected credentials.

### Environment

* Microsoft 365
* Microsoft Entra ID
* Microsoft 365 Admin Center

### Symptoms

* Microsoft 365 sign-in fails.
* User cannot access Microsoft 365 services.
* Account is present but authentication is denied.

### Investigation

* Located the affected account.
* Reviewed the user's sign-in status.
* Identified that sign-in was blocked.
* Tested the account to confirm the failure.

### Troubleshooting Steps

1. Opened **Microsoft 365 Admin Center → Users → Active users**.
2. Selected the affected user.
3. Blocked sign-in to simulate the incident.
4. Attempted to authenticate using the test account.
5. Confirmed that sign-in failed.
6. Returned to the Admin Center.
7. Changed the account setting to allow sign-in.
8. Allowed time for the change to propagate if necessary.
9. Attempted sign-in again.
10. Verified restored account access.

### Resolution

Sign-in was unblocked and the user successfully regained access to Microsoft 365.

### Root Cause

The user's account had sign-in disabled.

### Skills Used

* Microsoft 365 Admin Center
* Microsoft Entra ID
* Account Administration
* Authentication Troubleshooting
* Access Control
* Incident Verification

### Screenshot(s)

* Blocked sign-in setting
* Failed authentication
* Restored sign-in setting
* Successful authentication

### Lessons Learned

Learned how account-level sign-in restrictions affect authentication and how to verify both the problem and the resolution.

---