### Example 1: The first command creates DSC meta-configuration files for two servers for the Automation account named Contoso17.
```powershell
PS C:\> Get-AzAutomationDscOnboardingMetaconfig -AutomationAccountName Contoso17 -ComputerName Server01, -OutputFolder C:\Users\PattiFuller\Desktop -ResourceGroupName ResourceGroup03
```

