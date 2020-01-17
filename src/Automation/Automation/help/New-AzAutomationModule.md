### Example 1: This command imports a module named ContosoModule into the Automation account named Contoso17.
```powershell
PS C:\> New-AzAutomationModule -AutomationAccountName Contoso17 -ContentLinkUri http://contosostorage.blob.core.windows.net/modules/ContosoModule.zip -Name ContosoModule -ResourceGroupName ResourceGroup01
```

