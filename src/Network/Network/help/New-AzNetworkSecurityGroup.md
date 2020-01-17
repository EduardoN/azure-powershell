### Example 1: Step:1 Create a security rule allowing access from the Internet to port 3389.
```powershell
PS C:\> New-AzNetworkSecurityGroup -Location centralus -Name NSG-FrontEnd -ResourceGroupName TestRG -SecurityRules $rdpRule
```

