### Example 1: This command creates a probe configuration named MyProbe using the HTTP protocol.
```powershell
PS C:\> New-AzLoadBalancerProbeConfig -IntervalInSeconds 15 -Name MyProbe -Port 80 -ProbeCount 15 -Protocol http
```

