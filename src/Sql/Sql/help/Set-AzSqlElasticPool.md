### Example 1: The Set-AzSqlElasticPool cmdlet sets properties for an elastic pool in Azure SQL Database. This cmdlet can modify the eDTUs per pool (Dtu), storage max size per pool (StorageMB), maximum eDTUs per database (DatabaseDtuMax), and minimum eDTUs per database (DatabaseDtuMin).
```powershell
PS C:\> Set-AzSqlElasticPool -Dtu 1000 -Edition GeneralPurpose -ElasticPoolName ElasticPool01 -ResourceGroupName ResourceGroup01 -ServerName Server01
```

