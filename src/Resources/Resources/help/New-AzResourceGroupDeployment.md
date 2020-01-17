### Example 1: The New-AzResourceGroupDeployment cmdlet adds a deployment to an existing resource group.
```powershell
PS C:\> New-AzResourceGroupDeployment -Name mynewstorageaccount -ResourceGroupName ContosoEngineering -TemplateFile .storage-account-create-azdeploy.json -TemplateParameterObject <Hashtable>
```

