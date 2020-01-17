### Example 1: The Add-AzVhd cmdlet uploads on-premises virtual hard disks, in .vhd file format, to a blob storage account as fixed virtual hard disks.
```powershell
PS C:\> Add-AzVhd -Destination http://contosoaccount.blob.core.windows.net/vhdstore/win7baseimage.vhd -LocalFilePath C:\vhd\Win7Image.vhd -ResourceGroupName MyResourceGroup
```

