### Example 1: The Add-AzMetricAlertRule cmdlet adds or updates a metric-based alert rule.
```powershell
PS C:\> Add-AzMetricAlertRule -Action $alertingAction -Description Pura Vida -DisableRule  -Location East US -MetricName Requests -Name metricRule5 -Operator GreaterThan -ResourceGroupName Default-Web-EastUS -TargetResourceId /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/Default-Web-EastUS/providers/microsoft.web/sites/mywebsite -Threshold 1 -TimeAggregationOperator Average -WindowSize 00:05:00
```

