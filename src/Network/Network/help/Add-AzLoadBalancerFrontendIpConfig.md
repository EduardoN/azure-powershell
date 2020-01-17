### Example 1: The first command gets the Azure public IP address named MyPub and stores the result in the variable named $PublicIp.
```powershell
PS C:\> Add-AzLoadBalancerFrontendIpConfig -Name NewFrontend -PublicIpAddress $gwpip2
```

