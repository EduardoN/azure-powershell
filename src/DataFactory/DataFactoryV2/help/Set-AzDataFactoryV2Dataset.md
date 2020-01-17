### Example 1: The Set-AzDataFactoryV2Dataset cmdlet creates a dataset in Azure Data Factory.
```powershell
PS C:\> Set-AzDataFactoryV2Dataset -DataFactoryName WikiADF -DefinitionFile C:\samples\WikiSample\DA_WikipediaClickEvents.json -Force  -Name DAWikipediaClickEvents -ResourceGroupName ADF
```

