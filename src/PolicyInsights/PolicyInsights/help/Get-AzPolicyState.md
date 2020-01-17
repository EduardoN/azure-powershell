### Example 1: Gets latest policy state records generated in the last day for all resources within the subscription in current session context.
```powershell
PS C:\> Get-AzPolicyState -Filter ComplianceState eq 'NonCompliant'
```

