### Example 1: This command configures the active period for the data slices that the pipeline named DPWikisample processes.
```powershell
PS C:\> Set-AzDataFactoryPipelineActivePeriod -DataFactoryName WikiADF -EndDateTime 2014-05-22T16:00:00Z -PipelineName DPWikisample -ResourceGroupName ADF -StartDateTime 2014-05-21T16:00:00Z
```

