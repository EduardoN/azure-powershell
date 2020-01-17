### Example 1: The Restore-AzDataLakeStoreDeletedItem cmdlet restores a deleted file or folder in Data Lake Store. Requires the path of deleted item in trash returned by Get-AzDataLakeStoreDeletedItem.
```powershell
PS C:\> Restore-AzDataLakeStoreDeletedItem -Account ml1ptrashtest -Destination adl://ml1ptrashtest.azuredatalake.com/test0/file_1230 -Path 00000000-0000-0000-0000-000000000000 -Type file
```

