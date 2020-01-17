### Example 1: The Add-AzExpressRouteCircuitPeeringConfig cmdlet adds a peering configuration to an
```powershell
PS C:\> Add-AzExpressRouteCircuitPeeringConfig -ExpressRouteCircuit $ExpressRouteCircuit -Name AzurePrivatePeering -PeerASN 100 -PeeringType AzurePrivatePeering -PrimaryPeerAddressPrefix 123.0.0.0/30 -SecondaryPeerAddressPrefix 123.0.0.4/30 -VlanId 300
```

