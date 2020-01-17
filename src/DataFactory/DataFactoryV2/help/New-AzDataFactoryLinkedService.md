### Example 1: This command creates a linked service named LinkedServiceCuratedWikiData in the data factory named WikiADF.
```powershell
PS C:\> New-AzDataFactoryLinkedService -DataFactoryName WikiADF -File C:\samples\WikiSample\LinkedServiceCuratedWikiData.json -Name LinkedServiceCuratedWikiData -ResourceGroupName ADF
```

