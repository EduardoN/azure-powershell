### Example 1: The Test-AzLogicApp cmdlet validates a logic app definition in a resource group.
```powershell
PS C:\> Test-AzLogicApp -DefinitionFilePath d:\workflows\Definition.json -IntegrationAccountId {IntegrationAccountId} -Location westus -Name LogicApp01 -ParameterFilePath d:\workflows\Parameters.json -ResourceGroupName ResourceGroup11
```

