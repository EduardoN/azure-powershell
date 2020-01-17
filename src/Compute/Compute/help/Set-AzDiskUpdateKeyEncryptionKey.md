### Example 1: The first command creates a local empty disk update object with size 10GB in Premium_LRS storage account type.  It also sets Windows OS type and enables encryption settings.
```powershell
PS C:\> Set-AzDiskUpdateKeyEncryptionKey -DiskUpdate $diskupdateconfig -KeyUrl $keyUrl -SourceVaultId $keyId
```

