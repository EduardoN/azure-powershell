### Example 1: The Start-AzHDInsightJob cmdlet starts a defined Azure HDInsight job on a specified cluster.
```powershell
PS C:\> Start-AzHDInsightJob -ClusterName $clusterName -HttpCredential $clusterCreds -JobDefinition {JobDefinition} -ResourceGroupName $clusterResourceGroupName
```

