### Example 1: The Get-AzDiagnosticSetting cmdlet gets the categories and time grains that are logged for a resource.
```powershell
PS C:\> Get-AzDiagnosticSetting -DefaultProfile {DefaultProfile} -ResourceId /subscriptions/00000000-0000-0000-0000-000000000000/ResourceGroups/ContosoRG/providers/microsoft.keyvault/KeyVaults/ContosoKeyVault
```

