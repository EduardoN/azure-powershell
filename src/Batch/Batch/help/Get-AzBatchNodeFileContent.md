### Example 1: This command gets the node file that is named StdOut.txt, and saves it to the E:\PowerShell\StdOut.txt file path on the local computer.
```powershell
PS C:\> Get-AzBatchNodeFileContent -BatchContext $Context -DestinationPath E:\PowerShell\StdOut.txt -JobId Job01 -Path Startup\StdOut.txt -TaskId Task01
```

