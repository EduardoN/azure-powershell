### Example 1: The Set-AzSqlServerTransparentDataEncryptionProtector cmdlet sets the TDE protector for a SQL server.
```powershell
PS C:\> Set-AzSqlServerTransparentDataEncryptionProtector -Confirm  -Force  -ResourceGroupName ContosoResourceGroup -ServerName ContosoServer -Type AzureKeyVault
```

