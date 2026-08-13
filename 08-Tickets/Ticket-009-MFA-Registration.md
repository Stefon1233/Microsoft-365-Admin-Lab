# Ticket ##
Ticket 009 — MFA Registration

### Issue

User must complete Multi-Factor Authentication registration.

### User Report

User received an authentication-method/MFA prompt while signing in.

### Environment

* Microsoft Entra ID
* Microsoft 365
* Multi-Factor Authentication

### Symptoms

* User is prompted for additional authentication configuration.
* Microsoft 365 access cannot proceed normally until registration is completed.

### Investigation

Reviewed the user's authentication requirements and determined that MFA/authentication-method registration was required.

### Troubleshooting Steps

1. Signed in using the test user/admin account.
2. Received the MFA/authentication-method registration prompt.
3. Began the registration process.
4. Configured an available authentication method.
5. Completed verification.
6. Finished registration.
7. Signed out.
8. Signed back in.
9. Completed the authentication challenge when required.
10. Verified successful Microsoft 365 access.

### Resolution

The authentication method was registered successfully and the user completed MFA-protected authentication.

### Root Cause

The account required initial MFA/authentication-method registration.

### Skills Used

* Multi-Factor Authentication
* Microsoft Entra ID
* Authentication
* Identity Security
* Microsoft 365
* Account Verification

### Screenshot(s)

`Ticket-MFA.png`

### Lessons Learned

Practiced configuring MFA and learned how additional authentication factors improve account security beyond a password alone.

---