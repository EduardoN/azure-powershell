### Example 1: The Add-AzExpressRouteCircuitConnectionConfig cmdlet adds a circuit connection configuration to
```powershell
PS C:\> Add-AzExpressRouteCircuitConnectionConfig -AddressPrefix $addressSpace -ExpressRouteCircuit $circuit_init -Name $circuitConnectionName -PeerExpressRouteCircuitPeering $circuit_peer.Peerings[0].Id
```

