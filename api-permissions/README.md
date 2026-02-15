# Lab 8 — Microsoft Graph API Permissions Configuration

## Objective

Demonstrate how to configure Microsoft Graph API permissions for an application in Microsoft Entra ID to allow secure access to directory and user data.

This simulates real-world IAM scenarios where applications require controlled access to identity resources.

---

## What is Microsoft Graph?

Microsoft Graph is the primary API used to access:

• Users  
• Groups  
• Directory data  
• Applications  
• Authentication data  

It is heavily used in:

• IAM automation  
• Identity governance  
• Azure integrations  
• Enterprise applications  
• Security tools  

---

## Step 1 — View Existing API Permissions

Navigated to:

Entra ID → App registrations → IAM-Lab-App → API permissions

Verified default permission:

• User.Read (Delegated)

Screenshot:

screenshots/api-permissions-overview.png

---

## Step 2 — Add Microsoft Graph Permission

Clicked:

Add a permission → Microsoft Graph

Screenshot:

screenshots/add-permission.png

---

## Step 3 — Select Delegated Permissions

Selected:

Delegated permissions

This allows the application to act on behalf of a signed-in user.

Screenshot:

screenshots/delegated-permissions-selected.png

---

## Step 4 — Add Directory.Read.All Permission

Selected permission:

Directory.Read.All

Description:

Allows application to read directory data including:

• Users  
• Groups  
• Roles  
• Applications  

Screenshot:

screenshots/directory-read-all-selected.png

---

## Step 5 — Verify Permission Added

Confirmed Microsoft Graph permissions now include:

• User.Read  
• Directory.Read.All

Screenshot:

screenshots/permissions-added.png

---

## Security Note

Directory.Read.All requires admin consent because it grants access to sensitive directory information.

This permission is commonly used in:

• IAM tools  
• Automation scripts  
• Identity reporting tools  
• Security monitoring systems  

---

## Skills Demonstrated

• Microsoft Graph API integration  
• Application identity configuration  
• Delegated permissions management  
• Enterprise IAM configuration  
• Azure application security  

---

## Real-World Use Case

IAM engineers configure API permissions for:

• Automation tools  
• Identity governance systems  
• Azure applications  
• SSO integrations  
• Security monitoring tools  

This lab simulates production IAM application configuration.
