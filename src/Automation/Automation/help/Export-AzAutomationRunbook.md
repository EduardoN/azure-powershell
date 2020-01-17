### Example 1: The Export-AzAutomationRunbook cmdlet exports an Azure Automation runbook to a wps_2 script (.ps1 ) file, for wps_2 or wps_2 Workflow runbooks, or to a graphical runbook (.graphrunbook) file, for graphical runbooks.
```powershell
PS C:\> Export-AzAutomationRunbook -AutomationAccountName ContosoAutomationAccount -Name Runbook03 -OutputFolder C:\Users\PattiFuller\Desktop -ResourceGroupName ResourceGroup01
```

