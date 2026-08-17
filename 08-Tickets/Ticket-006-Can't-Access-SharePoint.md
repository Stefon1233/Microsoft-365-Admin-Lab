# Ticket ##
Ticket 006 — Can't Access SharePoint

### Issue

User cannot access the HR SharePoint site.

### User Report

User reported being unable to open the department's SharePoint resources.

### Environment

* Microsoft SharePoint Online
* Microsoft 365
* HR SharePoint Site

### Symptoms

* User can sign into Microsoft 365.
* Other Microsoft 365 services function normally.
* HR SharePoint content is inaccessible.

### Investigation

Reviewed the HR SharePoint site's permissions and determined that the test user did not have the required site access.

### Troubleshooting Steps

1. Removed the test user from the HR site's permissions.
2. Signed in as the test user.
3. Attempted to access the HR site.
4. Verified that access was denied.
5. Returned to SharePoint site permissions.
6. Added the user back with the appropriate permissions.
7. Signed in/tested again.
8. Verified successful access.

### Resolution

The user's SharePoint permissions were restored and the HR site became accessible.

### Root Cause

The user was missing the required SharePoint site permissions.

### Skills Used

* SharePoint Online
* Permissions Management
* Access Control
* Microsoft 365
* User Troubleshooting

### Screenshot(s)

* <img width="1440" height="876" alt="Non-Hr-Member-SharePoint-Access-Denied" src="https://github.com/user-attachments/assets/c3b37c65-4515-4619-8cfe-b8f3e3dcf1f3" />
* <img width="1440" height="876" alt="HR-Department-Site-Permissions" src="https://github.com/user-attachments/assets/4d16ae23-4e0d-4296-8e80-56c578984665" />
* <img width="1440" height="876" alt="Hr-Member-SharePoint-Access" src="https://github.com/user-attachments/assets/1e8ef758-e6c4-4fd5-9103-2cb33cefaba4" />


### Lessons Learned

Learned how SharePoint permissions affect individual site access and how to distinguish site-permission issues from general Microsoft 365 authentication problems.

---
