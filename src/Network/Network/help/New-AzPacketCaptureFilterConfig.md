### Example 1: In this example we create a packet capture named "PacketCaptureTest" with multiple filters and a time limit. Once the session is complete, it will be saved to the specified storage account. 
```powershell
PS C:\> New-AzPacketCaptureFilterConfig -LocalIPAddress 10.0.0.3 -LocalPort 1-65535 -Protocol TCP -RemoteIPAddress 1.1.1.1-255.255.255 -RemotePort 20;80;443
```

