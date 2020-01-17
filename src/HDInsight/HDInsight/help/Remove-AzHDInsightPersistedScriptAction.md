### Example 1: The Remove-AzHDInsightPersistedScriptAction cmdlet removes a persisted script action from the specified Azure HDInsight cluster's list of persisted script actions.
```powershell
PS C:\> Remove-AzHDInsightPersistedScriptAction -ClusterName your-hadoop-001 -Name $scriptActionName -ResourceGroupName MyResourceGroup
```

