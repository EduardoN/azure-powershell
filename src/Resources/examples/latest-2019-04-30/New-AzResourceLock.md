### Example 1: When you apply a lock at a parent scope, all child resources inherit the same lock.
```powershell
PS C:\> New-AzResourceLock -Force {Force} -LockLevel {LockLevel} -LockName ContosoSiteLock -LockNotes {LockNotes} -ResourceGroupName MyResourceGroup
```


