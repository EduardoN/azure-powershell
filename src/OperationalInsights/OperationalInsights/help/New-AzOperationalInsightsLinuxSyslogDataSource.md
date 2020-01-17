### Example 1: The New-AzOperationalInsightsLinuxSyslogDataSource cmdlet adds a syslog data source to connected Linux computers in a workspace.
```powershell
PS C:\> New-AzOperationalInsightsLinuxSyslogDataSource -CollectAlert  -CollectCritical  -CollectDebug  -CollectEmergency  -CollectError  -CollectInformational  -CollectNotice  -CollectWarning  -Facility {Facility} -Force  -Name MyStorageInsight -ResourceGroupName $ResourceGroupName -WorkspaceName ContosoWorkspace
```

