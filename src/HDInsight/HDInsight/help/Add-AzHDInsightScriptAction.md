### Example 1: The Add-AzHDInsightScriptAction cmdlet adds script actions to the HDInsight configuration object created by the New-AzHDInsightClusterConfig cmdlet.
```powershell
PS C:\> Add-AzHDInsightScriptAction -Config {Config} -Name $scriptActionName -NodeType HeadNode -Uri {Uri}
```

