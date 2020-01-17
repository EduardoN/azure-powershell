### Example 1: Use the New-AzRoleAssignment command to grant access.
```powershell
PS C:\> New-AzRoleAssignment -ObjectId $servicePrincipal.Id -RoleDefinitionName Contributor -Scope $storage.Id
```

