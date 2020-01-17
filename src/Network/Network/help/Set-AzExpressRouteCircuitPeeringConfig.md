### Example 1: The Set-AzExpressRouteCircuitPeeringConfig cmdlets saves a modified ExpressRoute peering
```powershell
PS C:\> Set-AzExpressRouteCircuitPeeringConfig -ExpressRouteCircuit $circuit_init -Name cert01 -PeerASN 100 -PeerAddressType IPv4 -PeeringType AzurePrivatePeering -PrimaryPeerAddressPrefix 123.0.0.0/30 -SecondaryPeerAddressPrefix 123.0.0.4/30 -VlanId 300
```

