### Example 1: This exports the total number of throttled Microsoft.Compute API calls.
```powershell
PS C:\> Export-AzLogAnalyticThrottledRequest -BlobContainerSasUri https://wkuotest1.blob.core.windows.net/mylogs?someSasUri -FromTime 2018-02-20T17:54:14.8806951-08:00 -GroupByResourceName  -Location West Central US -ToTime 2018-02-22T17:54:17.5832413-08:00
```

