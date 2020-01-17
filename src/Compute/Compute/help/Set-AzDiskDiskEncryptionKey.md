### Example 1: The first command creates a local empty disk object with size 5GB in Standard_LRS storage account type.  It also sets Windows OS type and enables encryption settings.
```powershell
PS C:\> Set-AzDiskDiskEncryptionKey -Disk $diskconfig -SecretUrl $secretUrl -SourceVaultId $secretId
```

