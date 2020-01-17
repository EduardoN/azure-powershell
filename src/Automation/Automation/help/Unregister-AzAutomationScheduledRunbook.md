### Example 1: The Unregister-AzAutomationScheduledRunbook cmdlet removes the association between an Azure Automation runbook and a schedule.
```powershell
PS C:\> Unregister-AzAutomationScheduledRunbook -AutomationAccountName Contoso17 -Force  -ResourceGroupName ResourceGroup01 -RunbookName Runbk01 -ScheduleName Runbk01Sched
```

