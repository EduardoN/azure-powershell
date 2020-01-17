### Example 1: This command provisions an Azure AD administrator group named DBAs for the managed instance named ManagedInstance01.
```powershell
PS C:\> Set-AzSqlInstanceActiveDirectoryAdministrator -DisplayName DBAs -InstanceName ManagedInstance01 -ObjectId 00000000-0000-0000-0000-000000000000 -ResourceGroupName ResourceGroup01
```

