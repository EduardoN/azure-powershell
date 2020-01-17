### Example 1: New-AzVpnClientIpsecParameter cmdlet is used to create the vpn ipsec parameters object of using the passed one or all parameters' values which user can set for any existing Virtual network gateway in ResourceGroup.
```powershell
PS C:\> New-AzVpnClientIpsecParameter -DhGroup DHGroup24 -IkeEncryption GCMAES256 -IkeIntegrity SHA384 -IpsecEncryption GCMAES256 -IpsecIntegrity GCMAES256 -PfsGroup PFS24 -SADataSize 429498 -SALifeTime 86473
```

