### Example 1: The New-AzAutomationCertificate cmdlet creates a certificate in Azure Automation.
```powershell
PS C:\> New-AzAutomationCertificate -AutomationAccountName Contoso17 -Exportable  -Name ContosoCertificate -Password $Password -Path ./cert.pfx -ResourceGroupName ResourceGroup01
```

