### Example 1: The Set-AzPolicyAssignment cmdlet modifies a policy assignment.
```powershell
PS C:\> Set-AzPolicyAssignment -Id $PolicyAssignment.ResourceId -Metadata {"category":"Virtual Machine"} -NotScope {NotScope}
```

