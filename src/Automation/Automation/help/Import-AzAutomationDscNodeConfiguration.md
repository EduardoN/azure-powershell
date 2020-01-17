### Example 1: This command imports a DSC node configuration from the file named webserver.mof into the Automation account named Contoso17, under the DSC configuration ContosoConfiguration.
```powershell
PS C:\> Import-AzAutomationDscNodeConfiguration -AutomationAccountName Contoso17 -ConfigurationName ContosoConfiguration -Force  -Path C:\DSC\webserver.mof -ResourceGroupName ResourceGroup01
```

