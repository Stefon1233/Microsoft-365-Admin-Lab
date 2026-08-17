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

* <img width="1440" height="876" alt="User-Details-Pre-Promotion" src="https://github.com/user-attachments/assets/8c3fd1d1-6b5a-43ef-b5fa-d9478d038322" />
* <img width="1440" height="876" alt="Manage-Admin-Roles" src="https://github.com/user-attachments/assets/e9329d72-adec-4202-813d-0709e1c56e30" />
* <img width="1440" height="876" alt="Admin-Roles-Updated" src="https://github.com/user-attachments/assets/d2297947-c43a-4dfc-aa26-a522a4bd8924" />
* <img width="1440" height="876" alt="User-Details-Pre-Promotion" src="https://github.com/user-attachments/assets/2fadd61d-b496-42af-839a-6770a2fdfc1e" />

### Lessons Learned

Practiced role-based access control and the principle of least privilege by granting administrative permissions only when required and removing them afterward.

---
