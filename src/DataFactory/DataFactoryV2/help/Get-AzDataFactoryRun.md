### Example 1: The Get-AzDataFactoryRun cmdlet gets the runs for a data slice of a dataset in Azure Data Factory.
```powershell
PS C:\> Get-AzDataFactoryRun -DataFactory $DataFactory -DatasetName DAWikiAggregatedData -DefaultProfile {DefaultProfile} -StartDateTime 2014-05-21T16:00:00Z
```

