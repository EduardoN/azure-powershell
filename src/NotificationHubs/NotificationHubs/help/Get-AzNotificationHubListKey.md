### Example 1: This command gets the primary and secondary connection strings for the authorization rule ListenRule, a rule assigned to the ContosoInternalHub notification hub.
```powershell
PS C:\> Get-AzNotificationHubListKey -AuthorizationRule ListenRule -Namespace ContosoNamespace -NotificationHub ContosoInternalHub -ResourceGroup ContosoNotificationsGroup
```

