### Example 1: The first command gets the load balancer that is associated with the front-end IP configuration you want to remove, and then stores it in the $loadbalancer variable.
```powershell
PS C:\> Remove-AzLoadBalancerFrontendIpConfig -LoadBalancer $loadbalancer -Name frontendName
```

