# Ticket ##
Ticket 008 — Teams Private Channel Access

### Issue

User cannot access the Accounts Payable private channel.

### User Report

User reported that the **Accounts Payable** channel was not visible in Microsoft Teams.

### Environment

* Microsoft Teams
* Microsoft 365
* Private Teams Channel

### Symptoms

* User can access the Team.
* Other channels are visible.
* Accounts Payable private channel is missing.

### Investigation

* Verified that the user belonged to the Team.
* Reviewed membership for the Accounts Payable private channel.
* Determined that the user was not a member of the private channel.

### Troubleshooting Steps

1. Opened Microsoft Teams.
2. Navigated to the Team containing **Accounts Payable**.
3. Reviewed private-channel membership.
4. Confirmed the affected user was missing.
5. Added the user to the private channel.
6. Saved the membership change.
7. Signed in/tested as the affected user.
8. Verified that Accounts Payable was visible and accessible.

### Resolution

The user was added to the Accounts Payable private channel and successfully gained access.

### Root Cause

The user was a member of the parent Team but was not separately assigned membership to the private channel.

### Skills Used

* Microsoft Teams
* Private Channels
* Membership Management
* Access Control
* Microsoft 365 Administration

### Screenshot(s)

<img width="1440" height="876" alt="Non-Hr-Member-SharePoint-Access-Denied" src="https://github.com/user-attachments/assets/7e84bbce-142e-4bbb-a503-b6c2941898ee" />

### Lessons Learned

Learned that membership in a Microsoft Team does not automatically provide access to its private channels.

---
