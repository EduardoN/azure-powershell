### Example 1: Creates an object of type Source.
```powershell
PS C:\> New-AzScheduledQueryRuleSource -DataSourceId <String> -Query Heartbeat | summarize AggregatedValue = count() by bin(TimeGenerated, 5m)
```

