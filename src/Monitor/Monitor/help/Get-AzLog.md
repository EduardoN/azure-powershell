### Example 1: The Get-AzLog cmdlet gets a log of events.
```powershell
PS C:\> Get-AzLog -EndTime Current date (time: 00:00:00 AM) + 1 day -ResourceId /subscriptions/00000000-0000-0000-0000-000000000000/ResourceGroups/Contoso-Web-CentralUS/providers/Microsoft.Web/ServerFarms/Contoso1 -StartTime EndTime - 7 days -Status {Status}
```

