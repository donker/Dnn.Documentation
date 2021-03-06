---
topic: create-host-account
locale: en
title: Create a Host Account
dnneditions: Platform,Evoq Content,Evoq Engage
dnnversion: 09.02.00
parent-topic: administrators-user-accounts-overview
related-topics: create-user-account,authorize-user,assign-user-to-multiple-roles,remove-user-from-multiple-roles,edit-user,manage-user-password,delete-user,delete-all-unauthorized-users,restore-deleted-user-account,purge-user-account,restore-multiple-deleted-users,purge-multiple-deleted-users,authorize-host,promote-user-to-host,demote-from-host,manage-host-password,delete-host,delete-all-unauthorized-hosts,restore-deleted-host-account,purge-host-account
---

# Create a Host Account

Hosts (also known as super users) have full permissions to all sites within the DNN instance. Only a host can promote/demote a user account to/from a host account.

Warning:

Hosts can revoke permissions from or demote another host.

## Prerequisites

*   **A host / super user account.** Hosts have full permissions to all sites in the DNN instance.

## Steps

1.  Go to Persona Bar \> Manage \> Users.
    
    ![Persona Bar > Manage > Users](img/scr-pbar-host-Manage-E91.png)
    
    ➊
    
    ➋
    
2.  Click/Tap Add User.
    
      
    
    ![Add User button](img/scr-UserList-AddUser-E90.png)
    
      
    
3.  Enter the user's information.
    
      
    
    ![Add New User](img/scr-AddNewUserInfo-E90.png)
    
      
    
    Field
    
    Description
    
    Authorized
    
    If enabled (On), the user is immediately subscribed to the Registered User role and to other roles that have Auto Assignment enabled. If disabled (Off), the user account is created but not authorized; an administrator must authorize the user account before the user can access areas of the website that are restricted to Registered User members.
    
    Random Password
    
    If enabled (On), generates a random password. Otherwise, you must provide a password.
    
    Password
    
    If the site is configured with password rules (i.e., minimum length), the initial password you assign must obey those password rules.
    
    Send an Email to New User
    
    If checked, the user is notified by email that the account is created. Can be checked at a later time to send the email belatedly.
    
4.  Search for the user account.
    
    *   Use the Search Users textbox at the top to search by a user account field, such as First Name, Last Name, User Name, or Email Address.
    *   Filter the displayed accounts by type, using the Show dropdown.
    
      
    
    ![User List > Search field and Show dropdown](img/scr-UserListSearchAndShow-E90.png)
    
      
    
5.  Click/Tap the ellipses icon for the user, then choose Make Superuser.
    
      
    
    ![User List > find the user > ellipses icon > Make Superuser](img/scr-UserList-ellipsesmenu-MakeSuperUser-E90.png)