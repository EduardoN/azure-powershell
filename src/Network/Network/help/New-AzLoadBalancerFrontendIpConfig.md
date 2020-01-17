### Example 1: The first command creates a dynamic public IP address named MyPublicIP in the resource group named MyResourceGroup, and then stores it in the $publicip variable.
```powershell
PS C:\> New-AzLoadBalancerFrontendIpConfig -Name $frontendName -PublicIpAddress $publicip
```

