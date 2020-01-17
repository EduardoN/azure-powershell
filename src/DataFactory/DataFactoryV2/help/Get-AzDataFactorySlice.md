### Example 1: The Get-AzDataFactorySlice cmdlet gets data slices for a dataset in Azure Data Factory.
```powershell
PS C:\> Get-AzDataFactorySlice -DataFactoryName WikiADF -DatasetName DAWikiAggregatedData -EndDateTime 2014-05-22T16:00:00Z -ResourceGroupName ADF -StartDateTime 2014-05-20T10:00:00Z
```

