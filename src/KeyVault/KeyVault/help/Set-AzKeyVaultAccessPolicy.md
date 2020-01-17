### Example 1: The Set-AzKeyVaultAccessPolicy cmdlet grants or modifies existing permissions for a user, application, or security group to perform the specified operations with a key vault. It does not modify the permissions that other users, applications, or security groups have on the key vault.
```powershell
PS C:\> Set-AzKeyVaultAccessPolicy -BypassObjectIdValidation  -ObjectId $account.Identity.PrincipalId -PermissionsToSecrets get -VaultName $VaultName
```

