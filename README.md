# IR-Scripting: Incident Response PowerShell Collection

This is a collection of PowerShell scripts designed to support and accelerate **Incident Response** workflows across common security platforms.

## Modules Covered

This repo is organized by PowerShell modules commonly used in IR:
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
-  [`PSFalcon`](./PSFalcon) – for CrowdStrike RTR-based automation and containment
- [`Defender`](./Defender) – (coming soon) for Microsoft Defender live response and artifact collection
- [`GraphAPI`](./GraphAPI) – (coming soon) for enrichment and identity-based investigation
- [`General`](./General) – for core forensic and response actions

## Usage

Each module folder includes:
- Scripts for real-world IR scenarios
- Comments explaining the context and use
- Sample input/output (where applicable)
- Guidance for adapting scripts in live environments

## 🚧 Work in Progress

This repo is actively growing. Expect new scripts, refactors, and documentation improvements regularly.
