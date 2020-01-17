### Example 1: The Get-AzNetworkWatcherNextHop cmdlet gets the next hop from a VM. 
```powershell
PS C:\> Get-AzNetworkWatcherNextHop -DestinationIPAddress 204.79.197.200 -NetworkWatcher $networkWatcher -SourceIPAddress $nics[0].IpConfigurations[0].PrivateIpAddress -TargetVirtualMachineId $VM.Id
```

