### Example 1: In this example, we assign a user assigned identity to an existing application gateway.
```powershell
PS C:\> Set-AzApplicationGatewayIdentity -ApplicationGateway $appgw -UserAssignedIdentityId $identity.Id
```

