### Example 1: The first command gets the virtual machine named VirtualMachine07 by using the Get-AzVM cmdlet.
```powershell
PS C:\> Add-AzVMSshPublicKey -KeyData MIIDszCCApugAwIBAgIJALBV9YJCF/tAMA0GCSq12Ib3DQEB21QUAMEUxCzAJBgNV -Path /home/admin/.ssh/authorized_keys -VM $VirtualMachine
```

