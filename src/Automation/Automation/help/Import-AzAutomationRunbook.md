### Example 1: The Import-AzAutomationRunbook cmdlet imports an Azure Automation runbook. Specify the 
```powershell
PS C:\> Import-AzAutomationRunbook -AutomationAccountName AutomationAccount01 -Force  -LogVerbose $True -Name Configuration01 -Path .GraphicalRunbook06.graphrunbook -Published  -ResourceGroupName ResourceGroup01 -Type PowerShell
```

