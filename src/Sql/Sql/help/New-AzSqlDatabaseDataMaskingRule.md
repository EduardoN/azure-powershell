### Example 1: The New-AzSqlDatabaseDataMaskingRule cmdlet creates a data masking rule for an Azure SQL database.
```powershell
PS C:\> New-AzSqlDatabaseDataMaskingRule -ColumnName Column01 -DatabaseName Database01 -MaskingFunction NoMasking -ResourceGroupName ResourceGroup01 -SchemaName Schema01 -ServerName Server01 -TableName Table01
```

