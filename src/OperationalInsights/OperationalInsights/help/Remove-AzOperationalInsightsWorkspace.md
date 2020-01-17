### Example 1: This command uses the Get-AzOperationalInsightsWorkspace cmdlet to get the workspace named MyWorkspace, and then passes it to the Remove-AzOperationalInsightsWorkspace cmdlet by using the pipeline operator to remove it.
```powershell
PS C:\> Remove-AzOperationalInsightsWorkspace -Force  -Name MyWorkspace -ResourceGroupName ContosResourceGroup
```

