### Example 1: This command adds the BGInfo extension to virtual machine named ContosoVM.
```powershell
PS C:\> Set-AzVMBginfoExtension -Location westus -Name AgentPool01 -ResourceGroupName MyResourceGroup -TypeHandlerVersion $typeVersion -VMName VM01
```

