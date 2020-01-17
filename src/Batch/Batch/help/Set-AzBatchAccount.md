### Example 1: The Set-AzBatchAccount cmdlet updates an Azure Batch account.
```powershell
PS C:\> Set-AzBatchAccount -AccountName cmdletexample -AutoStorageAccountId {AutoStorageAccountId} -ResourceGroupName MyResourceGroup -Tag @{key0=value0;key1=$null;key2=value2}
```

