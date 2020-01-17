### Example 1: This example adds an SSH public key to the VMSS.
```powershell
PS C:\> Add-AzVmssSshPublicKey -KeyData MIIDszCCApugAwIBAgIJALBV9YJCF/tAMA0GCSq12Ib3DQEB21QUAMEUxCzAJBgNV -Path /home/admin/.ssh/authorized_keys -VirtualMachineScaleSet $VMSS
```

