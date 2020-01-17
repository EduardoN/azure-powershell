### Example 1: This example creates a collection which will allow all traffic that matches either of the two rules.
```powershell
PS C:\> New-AzFirewallNetworkRuleCollection -ActionType Allow -Name MyNetworkRuleCollection -Priority 100 -Rule $netRule
```

