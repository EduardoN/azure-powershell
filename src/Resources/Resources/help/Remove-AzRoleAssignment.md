### Example 1: Use the Remove-AzRoleAssignment commandlet to revoke access to any principal at given scope and given role.
```powershell
PS C:\> Remove-AzRoleAssignment -ObjectId 00000000-0000-0000-0000-000000000000 -RoleDefinitionName Reader -Scope $ResourceGroup.ResourceId
```

