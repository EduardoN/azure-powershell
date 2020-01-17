### Example 1: The Set-AzVMOperatingSystem cmdlet sets operating system properties for a virtual machine.
```powershell
PS C:\> Set-AzVMOperatingSystem -ComputerName $ComputerName -Credential $Credential -CustomData $CustomData -EnableAutoUpdate  -ProvisionVMAgent  -VM $$VirtualMachine -WinRMHttp  -Windows 
```

