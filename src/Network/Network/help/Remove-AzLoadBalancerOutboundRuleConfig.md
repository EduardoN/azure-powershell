### Example 1: The first command gets the load balancer that is associated with the outbound rule configuration you want to remove, and then stores it in the $slb variable.
```powershell
PS C:\> Remove-AzLoadBalancerOutboundRuleConfig -LoadBalancer $slb -Name RuleName
```

