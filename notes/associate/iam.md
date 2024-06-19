IAM stands for **Identity and Access management**.

Since we can't restrict the account root user it's best practice to create ADMIN identity.

The principle of allowing the minimal sufficient access for an identity to perform necessary actions is called **least privileged access**. 

IAM is a globally resilient service but each account has a separate IAM instance, that's why we think of accounts as 'containers'. 

IAM let's you create 3 different types of **identity objects**

1- Users: People or applications that need access.  Examples: Aria, Backup account, etc
2- Groups: Groups of related people. Example: Developer team, Production team, HR team, etc 
3- Roles: External access OR used by AWS services 

**POLICIES** are what's actually granted or denied to the **identity objects**. 

What function does IAM have?

3- Authorize (to use some resource)
2- Authenticate (to login) 
1- Identity provider IDP (database of all identities)


IAM has as much power as the account root user.


There's **no cost** to IAM.

You can create a custom account **alias** or use the account **id** for your identites to login. 

