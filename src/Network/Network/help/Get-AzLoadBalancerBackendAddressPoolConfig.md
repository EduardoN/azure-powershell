### Example 1: The first command gets an existing load balancer named MyLoadBalancer in the resource group named MyResourceGroup, and then stores it in the $loadbalancer variable.
```powershell
PS C:\> Get-AzLoadBalancerBackendAddressPoolConfig -LoadBalancer $loadbalancer -Name BackendAddressPool02
```

