#Microsoft 365 Administration Lab 

##Overview

###Tasks Completed

####During this lab, I configured and administered a simulated Microsoft 365 business environment. Administrative tasks completed included:

######User & Identity Management
######Created and managed 10+ Microsoft 365 user accounts
######Configured user profiles, departments, job titles, and account information
######Reset user passwords and required password changes at next sign-in
######Blocked and restored user sign-in access
######Deleted and restored user accounts
######Managed Microsoft Entra ID users and groups
######Assigned and removed administrative roles
######Reviewed authentication and MFA settings
######Groups & Access Management
######Created Microsoft 365 groups
######Created security groups for department-based access
######Added and removed group members
######Configured group owners and members
######Created and managed distribution lists
######Demonstrated different levels of user access
######License Management
######Assigned Microsoft 365 licenses to users
######Removed licenses to simulate licensing problems
######Troubleshot users with missing licenses
######Reassigned licenses and verified restoration of Microsoft 365 services
######Exchange Online
######Administered Exchange Online through the Exchange Admin Center
######Created a Management shared mailbox
######Configured shared mailbox membership and permissions
######Configured Send As / mailbox delegation
######Created distribution lists
######Configured automatic replies
######Practiced mailbox administration as part of employee offboarding
######Microsoft Teams
######Created multiple department Teams
######Added owners and members
######Created standard channels
######Created a private channel
######Configured department-specific collaboration spaces
######Demonstrated differences in access based on Team membership
######SharePoint Online
######Created multiple SharePoint sites
######Configured site owners, members, and visitors
######Uploaded and managed documents
######Configured different permission levels
######Demonstrated department-based access restrictions
######Tested access using users with different permissions
######Demonstrated SharePoint document version history
######Viewed previous document versions and practiced version restoration
######Employee Lifecycle Administration
######Practiced employee onboarding and account configuration
######Blocked access during simulated employee termination
######Converted an employee mailbox to a shared mailbox
######Delegated mailbox access
######Configured an automatic reply
######Released the Microsoft 365 license
######Deleted the employee account
######Verified that the former employee could no longer sign in


###Help Desk Scenarios
####Ticket 001 — Password Reset

#####Issue:
######A user was unable to authenticate and required a password reset.

#####Troubleshooting & Resolution:
######Located the user in the Microsoft 365 Admin Center.
######Reset the user's password.
######Required the user to change the temporary password at next sign-in.
######Verified that the account was available for authentication.

#####Result: 
######Password reset completed successfully.

#####Skills Demonstrated: 
######User administration, password management, Microsoft 365 Admin Center

####Ticket 002 — Blocked Account

#####Issue: 
######A user was unable to access Microsoft 365 because sign-in was blocked.

#####Troubleshooting & Resolution:
######Reviewed the user's account status.
######Confirmed that sign-in was blocked.
######Tested the failed authentication scenario.
######Restored sign-in access.
######Verified that the account could authenticate again.

#####Result: 
######User access was successfully restored.

#####Skills Demonstrated: 
######Microsoft Entra ID, identity troubleshooting, account access management

####Ticket 003 — Missing Microsoft 365 License

#####Issue: 
######A user could not access licensed Microsoft 365 services.

#####Troubleshooting & Resolution:
######Reviewed the user's account and license status.
######Identified the missing Microsoft 365 license.
######Reassigned the appropriate license.
######Verified the user's licensing configuration after the change.

#####Result: 
######The user's Microsoft 365 license was successfully restored.

#####Skills Demonstrated: 
######License management, Microsoft 365 troubleshooting, user administration

####Ticket 004 — Employee Offboarding

#####Issue: 
######An employee was leaving the organization and required secure account offboarding.

#####Resolution:
######Blocked the employee's sign-in.
######Reset the account password.
######Converted the mailbox to a shared mailbox.
######Delegated mailbox access to an appropriate user.
######Configured an automatic reply.
######Removed/released the Microsoft 365 license.
######Deleted the employee account.
######Verified that the former employee could no longer authenticate.

#####Result: 
######The employee was successfully offboarded while appropriate mailbox access was retained.

#####Skills Demonstrated: 
######Employee lifecycle management, Exchange Online, identity security, license management

####Ticket 005 — Administrator Access

#####Issue: 
###### user temporarily required administrative permissions.

#####Resolution:
######Located the user in Microsoft Entra ID.
######Assigned the User Administrator role.
######Verified the role assignment.
######Removed the administrative role after testing.
######Verified that elevated access had been removed.

#####Result: 
######Administrative privileges were successfully granted and subsequently revoked.

#####Skills Demonstrated: 
######Microsoft Entra roles, RBAC, least privilege, administrative access management


###What I Learned

####This lab gave me hands-on experience administering a Microsoft 365 environment from both an administrator and end-user perspective. I learned how Microsoft Entra ID, Exchange Online, Microsoft Teams, SharePoint Online, and the Microsoft 365 Admin Center work together to support users across an organization.

####One of the most important lessons was understanding the relationship between identity, licensing, permissions, and service access. A user account existing in Microsoft 365 does not automatically mean that the user has access to every service. Licenses, group membership, roles, mailbox permissions, Teams membership, and SharePoint permissions can all affect what a user is able to access.

####I also gained experience with the user lifecycle, including creating accounts, configuring users, resetting passwords, assigning licenses, modifying access, and securely offboarding users. The offboarding scenario was particularly useful because it combined several administrative responsibilities, including blocking authentication, preserving mailbox data, delegating access, configuring automatic replies, releasing licenses, and removing the account.

####Working with Exchange Online helped me understand the differences between individual mailboxes, shared mailboxes, and distribution lists. I also practiced mailbox delegation and automatic reply configuration.

####Through Microsoft Teams and SharePoint, I learned how Microsoft 365 groups and permissions affect collaboration. Testing SharePoint with users who had different access levels demonstrated why proper permissions and group membership are important for protecting department-specific information.

####The troubleshooting scenarios also reinforced a structured help-desk approach: identify the reported problem, check the user's account and service configuration, determine the cause, make the appropriate administrative change, and verify that the issue is resolved.

####Overall, this project improved my confidence navigating Microsoft 365 administration tools and gave me practical experience with many of the tasks performed in Help Desk, IT Support, and junior Microsoft 365 administration roles.

###Skills Demonstrated

####Microsoft 365 Administration • Microsoft Entra ID • Exchange Online • Microsoft Teams • SharePoint Online • User & Group Management • Identity and Access Management • License Management • MFA • RBAC • Shared Mailboxes • Distribution Lists • Employee Onboarding & Offboarding • Help Desk Troubleshooting • Technical Documentation
