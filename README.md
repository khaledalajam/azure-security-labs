Hi, I'm Khaled, a Cybersecurity Analyst building real world hands-on expertise in identity and cloud security with a focus on Microsoft Azure. I'm preparing for the Microsoft Certified: Azure Security Engineer Associate (AZ-500) certification as part of my transition into a Cloud Security Engineer role. I thought I'd document some of it along the way.

To set the stage, the demos in this portfolio were built in an actual Azure subscription named "Prima-Macula Prod Sub 1" representing the organization "Prima-Macula" within the enviorment. This is not a sandbox; it's a production-like Azure setup, using the same services and security controls used in the industry.

Each demo begins with an overview diagram and then walks through a core security concept from setup to validation:

[Hybrid Identity & SSO](<Hybrid Identity with Seamless SSO.md>)

We're etting up hybrid identity between on-premises AD and Entra ID, with Seamless SSO for simplified user access.

[Privileged Access Management](<PAM Using Entra PIM.md>)


Privileged Identity Management (PIM) supports Azure RBAC roles, Entra ID roles, and group memberships. This demo focuses on Entra ID roles, which require Microsoft Entra ID P2 licensing to use PIM.



[Conditional Access](<Conditional Access Policy.md>)


We're going to create a simple conditional access policy for the pretend application registered within our Entra ID.



[Network Security Group](<Network Security Groups.md>) 

For this demo we're going to create and configure a network security group, or NSG for short, for our Windows VM to control the access to it.



>*This portfolio presents a focused selection of core cloud security concepts, demonstrated through hands-on Azure implementations. The principles shown are foundational and directly applicable across cloud platforms, including AWS and Google Cloud.*

