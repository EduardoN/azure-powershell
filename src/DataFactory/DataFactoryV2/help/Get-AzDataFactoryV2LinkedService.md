### Example 1: This command gets information about all linked services in the data factory named WikiADF, and then passes the linked services to the Format-List cmdlet by using the pipeline operator.
```powershell
PS C:\> Get-AzDataFactoryV2LinkedService -DataFactoryName WikiADF -ResourceGroupName ADF
```

