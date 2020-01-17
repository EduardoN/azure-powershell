### Example 1: This example adds a secret to the VMSS.
```powershell
PS C:\> Add-AzVmssSecret -SourceVaultId $Vault.ResourceId -VaultCertificate $CertConfig -VirtualMachineScaleSet $VMSS
```

