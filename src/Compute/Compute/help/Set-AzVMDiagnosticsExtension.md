### Example 1: This command uses the storage account name to enable diagnostics.
```powershell
PS C:\> Set-AzVMDiagnosticsExtension -DiagnosticsConfigurationPath diagnostics_publicconfig.xml -ResourceGroupName ResourceGroup01 -StorageAccountName MyStorageAccount -VMName VirtualMachine02
```

