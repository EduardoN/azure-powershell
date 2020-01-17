### Example 1: The Set-AzDtlAutoShutdownPolicy cmdlet sets the auto shutdown policy of a lab, which automatically shuts down all the virtual machines in the lab at a specified time of the day.
```powershell
PS C:\> Set-AzDtlAutoShutdownPolicy -Enable  -LabName {LabName} -ResourceGroupName MyResourceGroup -Time {Time}
```

