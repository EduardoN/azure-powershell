### Example 1: The Remove-AzAutomationDscNodeConfiguration cmdlet removes metadata from APS Desired State Configuration (DSC) node configurations in Azure Automation.
```powershell
PS C:\> Remove-AzAutomationDscNodeConfiguration -AutomationAccountName AutomationAccount01 -Force  -IgnoreNodeMappings  -Name Configuration01 -ResourceGroupName MyResourceGroup
```

