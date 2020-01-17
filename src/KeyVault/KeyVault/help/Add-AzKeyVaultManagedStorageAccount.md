### Example 1: Sets a Storage Account with Key Vault for its keys to be managed by Key Vault. The active key set
```powershell
PS C:\> Add-AzKeyVaultManagedStorageAccount -AccountName $sa.StorageAccountName -AccountResourceId $sa.Id -ActiveKeyName Primary -RegenerationPeriod $regenerationPeriod -VaultName $kv.VaultName
```

