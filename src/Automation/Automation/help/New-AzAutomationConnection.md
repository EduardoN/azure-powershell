### Example 1: The first command assigns a hash table of field values to the $FieldValue variable.
```powershell
PS C:\> New-AzAutomationConnection -AutomationAccountName AutomationAccount01 -ConnectionFieldValues $ClassicRunAsAccountConnectionFieldValues -ConnectionTypeName Azure -Name Connection12 -ResourceGroupName ResourceGroup01
```

