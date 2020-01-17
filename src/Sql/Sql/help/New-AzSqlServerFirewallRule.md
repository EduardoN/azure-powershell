### Example 1: This command creates a firewall rule named Rule01 on the server named Server01.
```powershell
PS C:\> New-AzSqlServerFirewallRule -EndIpAddress 192.168.0.199 -FirewallRuleName Rule01 -ResourceGroupName ResourceGroup01 -ServerName Server01 -StartIpAddress 192.168.0.198
```

