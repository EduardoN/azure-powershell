### Example 1: Sets an account SAS definition 'accountsas' on a KeyVault-managed storage account 'mysa' in vault 'mykv'. Specifically, the sequence above performs the following:
```powershell
PS C:\> Set-AzKeyVaultManagedStorageSasDefinition -AccountName $sa.StorageAccountName -Name accountsas -SasType account -TemplateUri $at -ValidityPeriod {ValidityPeriod} -VaultName $kv.VaultName
```

