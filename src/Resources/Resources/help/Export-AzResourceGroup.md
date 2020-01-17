### Example 1: The Export-AzResourceGroup cmdlet captures the specified resource group as a template and saves it to a JSON file.This can be useful in scenarios where you have already created some resources in your resource group, and then want to leverage the benefits of using template backed deployments.
```powershell
PS C:\> Export-AzResourceGroup -Force  -Resource /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/TestGroup/providers/Microsoft.Compute/virtualMachines/TestVirtualMachine -ResourceGroupName TestGroup -SkipAllParameterization 
```

