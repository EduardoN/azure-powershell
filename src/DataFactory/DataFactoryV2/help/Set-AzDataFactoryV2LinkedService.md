### Example 1: The Set-AzDataFactoryV2LinkedService cmdlet links a data store or a cloud service to Azure Data Factory.
```powershell
PS C:\> Set-AzDataFactoryV2LinkedService -DataFactoryName WikiADF -DefinitionFile C:\samples\WikiSample\LinkedServiceCuratedWikiData.json -Force  -Name LinkedServiceCuratedWikiData -ResourceGroupName ADF
```

