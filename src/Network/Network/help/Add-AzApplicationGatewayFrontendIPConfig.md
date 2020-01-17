### Example 1: The first command gets a virtual network named VNet01 that belongs to the resource group named ResourceGroup01, and stores it in the $VNet variable.
```powershell
PS C:\> Add-AzApplicationGatewayFrontendIPConfig -ApplicationGateway $AppGw -Name FrontEndIp01 -PrivateIPAddress 10.0.1.1 -Subnet $Subnet
```

