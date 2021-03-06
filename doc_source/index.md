# AWS Single Sign-On User Guide

-----
*****Copyright &copy; 2018 Amazon Web Services, Inc. and/or its affiliates. All rights reserved.*****

-----
Amazon's trademarks and trade dress may not be used in 
     connection with any product or service that is not Amazon's, 
     in any manner that is likely to cause confusion among customers, 
     or in any manner that disparages or discredits Amazon. All other 
     trademarks not owned by Amazon are the property of their respective
     owners, who may or may not be affiliated with, connected to, or 
     sponsored by Amazon.

-----
## Contents
+ [What Is AWS Single Sign-On?](what-is.md)
+ [Getting Started](getting-started.md)
   + [AWS SSO Prerequisites](prereqs.md)
   + [Enable AWS SSO](step1.md)
   + [Connect Your Directory](step2.md)
   + [Set Up SSO to Your AWS Accounts](step3.md)
   + [Set Up SSO to Your Cloud Applications](step4.md)
+ [Understanding Key AWS Single Sign-On Concepts](understanding-key-concepts.md)
   + [SAML Federation](samlfederationconcept.md)
   + [User Authentications](authconcept.md)
   + [Attribute Mappings](attributemappingsconcept.md)
   + [Permission Sets](permissionsetsconcept.md)
   + [Service-Linked Roles](slrconcept.md)
+ [Manage Your Connected Directory](manage-connected-directory.md)
   + [Connect AWS SSO to an AWS Managed Microsoft AD Directory](connectonpremad.md)
   + [Connect AWS SSO to an On-Premises Active Directory](connectawsad.md)
   + [Disconnect a Directory](howtodisconnectdirectory.md)
   + [Map Attributes in AWS SSO to Attributes in Your Connected Directory](mapssoattributestocdattributes.md)
+ [Manage SSO to Your AWS Accounts](manage-your-accounts.md)
   + [Single Sign-On Access](useraccess.md)
   + [Permission Sets](permissionsets.md)
   + [IAM Identity Provider](idp.md)
+ [Manage SSO to Your Applications](manage-your-applications.md)
   + [Cloud Applications](saasapps.md)
   + [Custom SAML 2.0 Applications](samlapps.md)
   + [Assign User Access](assignuserstoapp.md)
   + [Remove User Access](removeaccessfromapp.md)
   + [Map Attributes in Your Application to AWS SSO Attributes](mapawsssoattributestoapp.md)
+ [Authentication and Access Control for AWS SSO](iam-auth-access.md)
   + [Overview of Managing Access Permissions to Your AWS SSO Resources](iam-auth-access-overview.md)
   + [Using Identity-Based Policies (IAM Policies) for AWS SSO](iam-auth-access-using-id-policies.md)
   + [Using Service-Linked Roles for AWS SSO](using-service-linked-roles.md)
+ [Using the User Portal](using-the-portal.md)
   + [Tips for Using the Portal](portaltips.md)
   + [How to Sign In to the User Portal](howtosignin.md)
   + [How to Sign Out of the User Portal](howtosignout.md)
   + [How to Search for an AWS Account or Application](howtosearchforapp.md)
   + [How to Get Credentials of an IAM Role for Use with CLI Access to an AWS Account](howtogetcredentials.md)
+ [Logging AWS SSO API Calls with AWS CloudTrail](logging-using-cloudtrail.md)
+ [Limits in AWS SSO](limits.md)
+ [Troubleshooting AWS SSO Issues](troubleshooting.md)
+ [Document History](doc-history.md)
+ [AWS Glossary](glossary.md)