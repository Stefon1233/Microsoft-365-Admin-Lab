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

* <img width="1440" height="876" alt="Switch-To-Account-That-Has-Permission" src="https://github.com/user-attachments/assets/a426954c-43ca-4266-a455-f957fa8bcd34" />
* <img width="1440" height="876" alt="License-Removed-Test" src="https://github.com/user-attachments/assets/48511a20-d223-40b4-b8c0-fb01d2e8e551" />
* <img width="1440" height="876" alt="Pre-Adding-Licenses" src="https://github.com/user-attachments/assets/8c77cb38-b38d-47e9-8892-1afe0f5d6dd8" />
* <img width="1440" height="876" alt="Post-Adding-Licenses" src="https://github.com/user-attachments/assets/73550073-be7b-407c-a1ee-890a74669208" />



### Lessons Learned

Learned how Microsoft 365 licensing directly controls service availability and how to diagnose access problems caused by missing licenses.

---
