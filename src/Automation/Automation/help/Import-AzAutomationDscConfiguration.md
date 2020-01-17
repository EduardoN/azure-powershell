### Example 1: The Import-AzAutomationDscConfiguration cmdlet imports an APS Desired State Configuration (DSC) configuration into Azure Automation.
```powershell
PS C:\> Import-AzAutomationDscConfiguration -AutomationAccountName Contoso17-ResourceGroupName -Force  -Published  -ResourceGroupName MyResourceGroup -SourcePath C:\DSC\client.ps1
```

