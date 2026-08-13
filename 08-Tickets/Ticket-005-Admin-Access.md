# Ticket ##
Ticket 005 — Admin Access

### Issue

User requires temporary User Administrator privileges.

### User Report

A user requires elevated permissions to perform Microsoft 365 user-administration tasks.

### Environment

* Microsoft 365
* Microsoft Entra Admin Center
* Microsoft 365 Admin Center

### Symptoms

* User cannot perform administrative user-management tasks.
* Required administrative options are unavailable.

### Investigation

* Reviewed the user's current role assignments.
* Confirmed that User Administrator was not assigned.
* Determined that temporary elevation was required.

### Troubleshooting Steps

1. Located the test user.
2. Reviewed existing roles.
3. Assigned the **User Administrator** role.
4. Saved the change.
5. Verified the role assignment.
6. Tested administrative access.
7. Confirmed that permitted administrative functions were available.
8. Removed the User Administrator role.
9. Verified the role was no longer assigned.
10. Tested access again.
11. Confirmed that elevated administrative access was removed.

### Resolution

Temporary User Administrator access was successfully assigned, tested, and removed.

### Root Cause

The user's normal account did not have the administrative role required for the temporary task.

### Skills Used

* Microsoft Entra ID
* Role-Based Access Control
* User Administrator
* Privileged Access
* Least Privilege
* Microsoft 365 Administration

### Screenshot(s)

* Role before assignment
* User Administrator assignment
* Successful administrative access
* Role removal
* Verification after removal

### Lessons Learned

Practiced role-based access control and the principle of least privilege by granting administrative permissions only when required and removing them afterward.

---