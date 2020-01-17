### Example 1: The Remove-AzADSpCredential cmdlet can be used to remove a credential key from a service principal in the case of a compromise or as part of credential key rollover expiration.
```powershell
PS C:\> Remove-AzADSpCredential -Force  -KeyId 00000000-0000-0000-0000-00000007ebb -ObjectId 00000000-0000-0000-0000-000000000000
```

