### Example 1: The first command creates an Autoscale rule named Requests, and then stores it in the $Rule variable.
```powershell
PS C:\> New-AzAutoscaleProfile -DefaultCapacity 1 -MaximumCapacity 10 -MinimumCapacity 1 -Name Profile01 -Rule $Rule
```

