# Where to start with Microsoft 365 ?

Microsoft 365 has become the cornerstone of office collaboration for most companies in nowadays.

However, the long-term retrieval of acquired learning content with permanent safeguarding of the retrieval systems, the protection of data and thus also privacy poses proliferation and resource sustainability challenges to the actors.

For Microsoft 365 engineers it's quite important, to have a lab where to test processed hardening guides, automation and compliance stuff.

So, where to start with?

Here a list of possibilities:
- start with a Microsoft Sharepoint site: https://www.microsoft.com/en-us/microsoft-365/sharepoint/compare-sharepoint-plans
- start with a Microsoft 365 business plan: https://www.microsoft.com/en-us/microsoft-365/business/compare-all-microsoft-365-business-products
- start with a Microsoft 365 enterprise business plan: https://www.microsoft.com/en-us/microsoft-365/enterprise/office365-plans-and-pricing
- start by joining the Microsoft 365 Developer Program: https://developer.microsoft.com/en-us/microsoft-365
- check the availability of a domain name: https://o365.rocks/

Setting up a sharepoint site has the advantage of low upfront costs. Usually you get a one month free trial for various licenses as well.

Starting a Microsoft 365 business plan is the path for production.
Most users still work with the desktop versions of Microsoft Office products. The goal of Microsoft 365 Business standard is interoperability and compatibility. The disadvantage of those workflows in general is risk such as dataloss, malware, ransomware, identity theft, rogue devices, network penetration, etc.

A good overview with all different plans and add-ons is available on this [weblink](https://go.microsoft.com/fwlink/p/?LinkID=2139145&clcid=0x409&culture=en-us&country=us).  
See a copy of it [here](https://github.com/user-attachments/files/16452804/modern-work-plan-comparison-enterprise-352528.pdf) .

This wiki describes journey experiences and tecniques automating M365 tenant configurations.

Lab-Environment
-

First, start by creating a [Sharepoint site (Plan 1)](https://github.com/dcasota/m365-scripts/wiki/Create-and-configure-a-new-sharepoint-site-(plan-1))  

Have a look to the Wiki entries about Microsoft 365, Teams, Sharepoint [here](https://github.com/dcasota/m365-scripts/wiki).

As-a-code configuration
-
Starting with a Microsoft 365 tenant typically leads to the demand of desired configurations. Microsoft365DSC is the declarative form of a Microsoft 365 tenant configuration. It allows you to represent the configuration of your tenant in code (Configuration-as-Code) leveraging PowerShell Desired State Configuration (DSC). For more information, see https://microsoft365dsc.com/user-guide/get-started/introduction/.

DSC implementations use various Powershell modules. It helps to get familiar with the Powershell modules and with the supported authentication methods.

![image](https://github.com/user-attachments/assets/2dc570d7-6fdf-4f25-9c15-f7e7c0798cf0)

For learning purposes, see
- https://learn.microsoft.com/en-us/training/paths/manage-microsoft-365-services-use-windows-powershell/



