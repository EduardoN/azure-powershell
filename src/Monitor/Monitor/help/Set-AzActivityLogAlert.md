### Example 1: The first four commands create leaf condition and action group.
```powershell
PS C:\> Set-AzActivityLogAlert -Action $actionGrp1 -Condition $condition1, -Location $location -Name $alertName -ResourceGroupName $resourceGroupName -Scope scope1,scope2
```

