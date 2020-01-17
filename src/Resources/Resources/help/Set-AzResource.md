### Example 1: The Set-AzResource cmdlet modifies an existing Azure resource.
```powershell
PS C:\> Set-AzResource -Force  -ResourceId /subscriptions/$subscriptionId/resourceGroups/$resourceGroupName/providers/Microsoft.EventHub/namespaces/$namespaceName -Tag @{Name=CostCenter}
```

