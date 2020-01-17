### Example 1: The Set-AzVMADDomainExtension cmdlet adds an Azure Active Directory (AD) domain virtual machine extension to a virtual machine.
```powershell
PS C:\> Set-AzVMADDomainExtension -Credential $vmCred -DomainName <String> -JoinOption {JoinOption} -Name AgentPool01 -ResourceGroupName MyResourceGroup -Restart  -TypeHandlerVersion $typeVersion -VMName VM01
```

