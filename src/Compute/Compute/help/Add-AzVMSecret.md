### Example 1: The first command creates a virtual machine object, and then stores it in the $VirtualMachine variable.
```powershell
PS C:\> Add-AzVMSecret -CertificateStore $CertificateStore01 -CertificateUrl $CertUrl -SourceVaultId $SourceVaultId -VM $VM
```

