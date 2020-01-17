### Example 1: The first command converts a string into a secure string by using the ConvertTo-SecureString
```powershell
PS C:\> Set-AzKeyVaultSecret -Name $KeyVaultSecretName -SecretValue $Secret -VaultName $VaultName
```

