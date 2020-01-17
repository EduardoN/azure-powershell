### Example 1: The Add-AzApiManagementRegion cmdlet adds new instance of type PsApiManagementRegion to the collection of AdditionalRegions of provided instance of type Microsoft.Azure.Commands.ApiManagement.Models.PsApiManagement.
```powershell
PS C:\> Add-AzApiManagementRegion -ApiManagement $ApiManagement -Capacity 2 -Location $secondarylocation -VirtualNetwork $additionalRegionVirtualNetwork
```

