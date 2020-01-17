### Example 1: This command creates an IP configuration object named ContosoVmssInterface03, and then stores it in the $IPConfiguration variable for later use.
```powershell
PS C:\> New-AzVmssIpConfig -LoadBalancerBackendAddressPoolsId {LoadBalancerBackendAddressPoolsId} -LoadBalancerInboundNatPoolsId {LoadBalancerInboundNatPoolsId} -Name AgentPool01 -SubnetId {SubnetId}
```

