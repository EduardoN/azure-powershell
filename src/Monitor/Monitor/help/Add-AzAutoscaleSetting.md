### Example 1: The first two commands use New-AzAutoscaleRule to create two Autoscale rules, $Rule1 and $Rule2.
```powershell
PS C:\> Add-AzAutoscaleSetting -AutoscaleProfile $Profile1, -Location East US -Name MySetting -ResourceGroupName Default-Web-EastUS -TargetResourceId /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/Default-Web-EastUS/providers/microsoft.web/serverFarms/DefaultServerFarm
```

