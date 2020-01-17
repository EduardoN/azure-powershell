### Example 1: The New-AzTrafficManagerProfile cmdlet creates an Azure Traffic Manager profile.
```powershell
PS C:\> New-AzTrafficManagerProfile -MonitorPath /default.aspx -MonitorPort 80 -MonitorProtocol HTTP -Name ContosoProfile -ProfileStatus Enabled -RelativeDnsName contosoapp -ResourceGroupName ResourceGroup11 -TrafficRoutingMethod Performance -Ttl <UInt32>
```

