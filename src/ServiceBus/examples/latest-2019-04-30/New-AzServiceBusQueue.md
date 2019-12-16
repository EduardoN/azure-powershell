### Example 1: Creates or updates a Service Bus queue.
```powershell
PS C:\> New-AzServiceBusQueue -EnablePartitioning  -MaxSizeInMegabytes {MaxSizeInMegabytes} -Name SB-Queue_example1 -Namespace {Namespace} -ResourceGroupName MyResourceGroup
```

