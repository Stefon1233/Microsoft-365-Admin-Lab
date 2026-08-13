 m# Ticket ##
Ticket 001 — Password Reset

## Issue

Cannot authenticate / password reset required.

## User Report

**User:** Amanda Taylor
Amanda reported that she could not sign in to her account with her existing password.

## Environment

* Microsoft 365
* Microsoft Entra ID
* Microsoft 365 Admin Center
* Windows/Web Browser

## Symptoms

* User cannot authenticate.
* Existing password is not accepted.
* Account requires administrator assistance.

## Investigation

* Located Amanda Taylor in the Microsoft 365 Admin Center.
* Verified that the correct user account was being used.
* Confirmed the account was active.
* Determined that a password reset was appropriate.

## Troubleshooting Steps

1. Opened the Microsoft 365 Admin Center.
2. Navigated to **Users → Active users**.
3. Selected Amanda Taylor.
4. Reset the user's password.
5. Generated/set a temporary password.
6. Enabled **Require this user to change their password when they first sign in**.
7. Provided the temporary credentials to the test user.
8. Attempted sign-in as Amanda Taylor.
9. Changed the password when prompted.
10. Verified successful authentication.

## Resolution

Amanda Taylor's password was successfully reset. The user changed the temporary password during the next sign-in and regained access.

## Root Cause

The user's existing credentials were no longer allowing successful authentication.

## Skills Used

* Microsoft 365 Administration
* User Account Management
* Password Reset
* Identity and Access Management
* Authentication Troubleshooting
* Microsoft Entra ID

## Screenshot(s)

<img width="1440" height="876" alt="New-User-Updated-Password-Unknown" src="https://github.com/user-attachments/assets/93fbff38-c8b7-427e-bfcc-1382961cbd18" />

<img width="1440" height="788" alt="New-User-Update-Password-Upon-Signing-In" src="https://github.com/user-attachments/assets/dc73eae1-bbdd-4feb-8ebb-e9ed40c509f9" />

<img width="1440" height="876" alt="Password-Has-Been-Reset" src="https://github.com/user-attachments/assets/e57f4e7c-1075-4256-bbd7-98749121966a" />


## Lessons Learned
Practiced securely resetting Microsoft 365 credentials, requiring a password change, and verifying that access was restored.
