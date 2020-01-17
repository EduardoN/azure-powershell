### Example 1: U-SQL script parameters are prepended above the main script contents, e.g.:
```powershell
PS C:\> Submit-AzDataLakeAnalyticsJob -Account ContosoAdlAccount -AnalyticsUnits 32 -Name New Job -ScriptParameter $parameters -ScriptPath $LocalScriptPath
```

