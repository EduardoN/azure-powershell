### Example 1: The New-AzAutomationWebhook cmdlet creates a webhook for an Azure Automation runbook.
```powershell
PS C:\> New-AzAutomationWebhook -AutomationAccountName AutomationAccount01 -ExpiryTime 10/2/2016 -Force  -IsEnabled $True -Name Webhook06 -ResourceGroupName ResourceGroup01 -RunbookName ContosoRunbook
```

