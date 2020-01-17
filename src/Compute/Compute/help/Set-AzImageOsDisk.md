### Example 1: The first command creates an image object, and then stores it in the $imageConfig variable.
```powershell
PS C:\> Set-AzImageOsDisk -BlobUri $osDiskVhdUri -Image $imageConfig -OsState Generalized -OsType Windows
```

