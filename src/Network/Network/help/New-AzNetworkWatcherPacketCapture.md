### Example 1: The New-AzNetworkWatcherPacketCapture cmdlet creates a new packet capture resource and starts a packet capture session on a VM.
```powershell
PS C:\> New-AzNetworkWatcherPacketCapture -Filter $filter1, -NetworkWatcher $networkWatcher -PacketCaptureName PacketCaptureTest -StorageAccountId $storageAccount.id -TargetVirtualMachineId $vm.Id -TimeLimitInSeconds 60
```

