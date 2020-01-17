### Example 1: The Register-AzAutomationScheduledRunbook cmdlet associates an Azure Automation runbook to a schedule.
```powershell
PS C:\> Register-AzAutomationScheduledRunbook -AutomationAccountName Contoso17 -Parameters $Params -ResourceGroupName ResourceGroup01 -RunbookName Runbk01 -ScheduleName Sched01
```

