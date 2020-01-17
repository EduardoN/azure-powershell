### Example 1: This command sets the status of all slices for the dataset named DAWikiAggregatedData to Waiting in the data factory named WikiADF.
```powershell
PS C:\> Set-AzDataFactorySliceStatus -DataFactoryName WikiADF -DatasetName DAWikiAggregatedData -EndDateTime 2014-05-21T20:00:00Z -ResourceGroupName ADF -StartDateTime 2014-05-21T16:00:00Z -Status Failed -UpdateType Individual
```

