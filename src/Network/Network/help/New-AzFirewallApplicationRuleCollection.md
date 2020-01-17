### Example 1: This example creates a collection with one rule. All traffic that matches the conditions identified in $rule1 will be allowed.
```powershell
PS C:\> New-AzFirewallApplicationRuleCollection -ActionType Allow -Name MyAppRuleCollection -Priority 100 -Rule $appRule
```

