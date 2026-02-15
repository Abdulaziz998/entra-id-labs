# Lab 7 — Enterprise Application Registration (App Registration & Service Principal)

## Objective

Demonstrate how to register an application in Microsoft Entra ID and verify the associated Enterprise Application (Service Principal) used for authentication and access control.

---

## Actions Performed

### Step 1 — Register Application
Created a new application registration:

Name: IAM-Lab-App  
Supported account types: Single tenant  

Screenshot:
screenshots/app-registration-form.png

---

### Step 2 — Verify Application Registration

Verified application identity details:

• Application ID  
• Object ID  
• Tenant ID  
• Application status  

Screenshot:
screenshots/app-registration-overview.png

---

### Step 3 — Verify Enterprise Application Creation

Confirmed Enterprise Application (Service Principal) was automatically created.

Screenshot:
screenshots/enterprise-app-list.png

---

### Step 4 — Assign User to Enterprise Application

Assigned user:

IAM-Test-User1iam.test1

Verified user assignment successfully.

Screenshot:
screenshots/enterprise-app-user-assigned.png

---

## What This Demonstrates

• Application identity creation  
• Service Principal creation  
• Identity-to-application trust relationship  
• Access assignment to applications  

---

## IAM Concepts Demonstrated

• App Registration  
• Enterprise Applications  
• Service Principals  
• Identity-based access to applications  
• Microsoft Entra ID application authentication

---

## Real-World Use Cases

This is used for:

• Single Sign-On (SSO)
• Azure integrations
• OAuth authentication
• API authentication
• Service accounts
• Automation
• Enterprise IAM architecture
