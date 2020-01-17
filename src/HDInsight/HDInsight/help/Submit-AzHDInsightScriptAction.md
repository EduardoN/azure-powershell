### Example 1: The Submit-AzHDInsightScriptAction cmdlet submits a new script action to an Azure HDInsight cluster.
```powershell
PS C:\> Submit-AzHDInsightScriptAction -ClusterName your-hadoop-001 -Name $scriptActionName -NodeTypes HeadNode -Parameters {Parameters} -Uri {Uri}
```

