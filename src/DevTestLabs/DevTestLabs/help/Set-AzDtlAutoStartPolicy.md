### Example 1: The Set-AzDtlAutoStartPolicy cmdlet sets the auto start policy of a lab, which allows lab virtual machines to be scheduled for automatic start.
```powershell
PS C:\> Set-AzDtlAutoStartPolicy -Days Sunday -Enable  -LabName {LabName} -ResourceGroupName MyResourceGroup -Time {Time}
```

