### Example 1: The New-AzADAppCredential cmdlet can be used to add a new credential or to roll credentials for an application.
```powershell
PS C:\> New-AzADAppCredential -EndDate $cer.NotAfter -ObjectId 00000000-0000-0000-0000-000000000000 -Password $SecureStringPassword -StartDate $cer.NotBefore
```

