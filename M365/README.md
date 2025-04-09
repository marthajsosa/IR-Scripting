# M365
<blockquote>This folder contains scripts related to M365 </blockquote>

Scripts in this section are meant to help automate and streamline investigations and remediation in M365.

## Modules Covered

This repo is organized by PowerShell modules commonly used by Incident Response in M365:
- ### [`Exchange Online Management`](./ExchangeOnlineManagement) – for email trace, auditing, and phishing investigation
    - References:
        - [Install Exchange-Online Module](https://www.powershellgallery.com/packages/ExchangeOnlineManagement/3.7.2)
        - [Connect to Exchange-Online](https://learn.microsoft.com/en-us/powershell/exchange/connect-to-exchange-online-powershell?view=exchange-ps)
        - [Exchange-Online](https://learn.microsoft.com/en-us/powershell/exchange/exchange-online-powershell-v2?view=exchange-ps)
        - [Permissions in Exchange-Online](https://learn.microsoft.com/en-us/exchange/permissions-exo/permissions-exo)
- ### [`SharePoint Online Management`](./SharepointOnlineManagement)
    - References:
        - [Install and connect to SharePoint Online Management](https://learn.microsoft.com/en-us/training/modules/manage-sharepoint-online-use-windows-powershell/2-install-connect-sharepoint-online-management-shell)
        - [Manage Users and Groups](https://learn.microsoft.com/en-us/training/modules/manage-sharepoint-online-use-windows-powershell/3-manage-sharepoint-online-users-groups)
        - [Manage sites](https://learn.microsoft.com/en-us/training/modules/manage-sharepoint-online-use-windows-powershell/4-manage-sharepoint-sites)
        - [Manage External Users](https://learn.microsoft.com/en-us/training/modules/manage-sharepoint-online-use-windows-powershell/5-manage-sharepoint-online-external-user-sharing)

## Modules Setup

Before using the scripts in this folder, make sure you have the module installed and authenticated for the following modules:

```powershell
Install-Module -Name MicrosoftTeams
```
