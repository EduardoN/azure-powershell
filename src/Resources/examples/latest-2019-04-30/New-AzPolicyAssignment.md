### Example 1: This operation creates or updates a policy assignment with the given scope and name.
```powershell
PS C:\> New-AzPolicyAssignment -DefaultProfile {DefaultProfile} -Name RestrictLocationPolicyAssignment -PolicyDefinition {PolicyDefinition} -Scope /subscriptions/$($Subscription.Id)
```


