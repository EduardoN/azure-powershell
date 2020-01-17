### Example 1: The first command gets the DSC node for the computer named Computer14 in the Automation account named Contoso17.
```powershell
PS C:\> Get-AzAutomationDscNodeReport -AutomationAccountName Contoso17 -Latest  -NodeId $Node.Id -ResourceGroupName ResourceGroup03
```

