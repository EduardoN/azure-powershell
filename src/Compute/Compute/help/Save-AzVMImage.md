### Example 1: The Save-AzVMImage cmdlet saves a virtual machine as a VMImage.
```powershell
PS C:\> Save-AzVMImage -DestinationContainerName VMContainer01 -Name VirtualMachine07 -Path /home/admin/.ssh/authorized_keys -ResourceGroupName ResourceGroup11 -VHDNamePrefix VM07
```

