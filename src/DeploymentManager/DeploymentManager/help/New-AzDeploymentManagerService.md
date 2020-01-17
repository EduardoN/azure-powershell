### Example 1: The New-AzDeploymentManagerService cmdlet creates a service under a service topology, and returns an object that represents that service.
```powershell
PS C:\> New-AzDeploymentManagerService -Location Central US -Name ContosoService1 -ServiceTopologyObject {ServiceTopologyObject} -TargetLocation East US -TargetSubscriptionId XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX
```

