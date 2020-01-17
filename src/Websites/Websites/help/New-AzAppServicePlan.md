### Example 1: This command creates an App Service plan named ContosoASP in the resource group named Default-Web-WestUS in Geo location West US.
```powershell
PS C:\> New-AzAppServicePlan -Location West US -Name ContosoASP -NumberofWorkers 1 -ResourceGroupName Default-Web-WestUS -Tier Free -WorkerSize Small
```

