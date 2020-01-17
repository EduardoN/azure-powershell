### Example 1: The Set-AzVMADDomainExtension cmdlet adds an Azure Active Directory (AD) domain virtual machine extension to a virtual machine.
```powershell
PS C:\> Set-AzVMADDomainExtension -Credential $vmCred -DomainName <String> -ForceRerun {ForceRerun} -JoinOption {JoinOption} -OUPath {OUPath} -ResourceGroupName MyResourceGroup -Restart  -VMName VM01
```

