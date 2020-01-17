### Example 1: This command creates an elastic pool in the Standard service tier named ElasticPool01. The server
```powershell
PS C:\> New-AzSqlElasticPool -DatabaseDtuMax 100 -DatabaseDtuMin 10 -Dtu 400 -Edition GeneralPurpose -ElasticPoolName ElasticPool01 -ResourceGroupName ResourceGroup01 -ServerName Server01
```

