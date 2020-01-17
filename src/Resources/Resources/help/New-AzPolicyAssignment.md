### Example 1: The first command gets a resource group named ResourceGroup11 by using the Get-AzResourceGroup cmdlet.
```powershell
PS C:\> New-AzPolicyAssignment -Name RestrictLocationPolicyAssignment -PolicyDefinition $Policy -PolicyParameterObject $AllowedLocations -Scope $ResourceGroup.ResourceId
```

