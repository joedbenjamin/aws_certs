# IAM

- identity access management is used to manage **access** to users and resources
- IAM is a universal system, (applied to all regions at the same time)
- a free service
- a root account is the account initially created when AWS is set up (full admin)
- new IAM accounts have no permissions by default until granted
- new users get assigned an Access Key Id and Secret when first created when you give them programmitic access
- access keys are only used for CLI and SDK (cannot access console)
- access keys are only shown once when created. if lost they must be deleted/recreated again
- always set up MFA for root accounts
- users must enable MFA on their own, admin cannot turn it on for each user
- IAM allows your set password policies to set min requirements or rotate passwords
- **iam idetities** as users, groups and roles
- **iam users** end users who log into the console or interact with AWS resources programmatically
- **iam groups** group up your users so they all share permission levels of the group e.g. (admins, developers, auditors)
- **iam roles** associate permissions to a role and then assign this to users or groups
- **iam policies** JSON documents which grant permissions for a specific user, group, or role to access services.
  - policies are attached to IAM identities
- **managed policies** are policies provided by AWS and cannot be edited
- **customer managed policies** are policies created by you, the customer which you can edit
- **inline policies** are policies which are directly attached to a user
