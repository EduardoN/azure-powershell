### Example 1: The Remove-AzADAppCredential cmdlet can be used to remove a credential key from an application in the case of a compromise or as part of credential key rollover expiration.
```powershell
PS C:\> Remove-AzADAppCredential -Force  -KeyId 00000000-0000-0000-0000-00000007ebb -ObjectId 00000000-0000-0000-0000-000000000000
```

