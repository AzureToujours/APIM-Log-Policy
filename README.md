# APIM-Log-Policy

1. Install [Create-AzDiagPolicy](https://learn.microsoft.com/en-us/azure/azure-monitor/essentials/diagnostic-settings-policy#custom-policy-definitions).
2. Run the following script and select *Microsoft.ApiManagement/service*
```powershell
Create-AzDiagPolicy.ps1 -ExportLA -ExportEH -ExportDir "C:\temp\policyfiles"
```
