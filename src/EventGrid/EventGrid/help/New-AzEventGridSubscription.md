### Example 1: Create a new event subscription to an Azure Event Grid topic, a supported Azure resource, an Azure subscription or Resource Group.
```powershell
PS C:\> New-AzEventGridSubscription -Endpoint /subscriptions/00000000-0000-0000-0000-000000000000/resourceGroups/TestRG/providers/Microsoft.EventHub/namespaces/ContosoNamespace/eventhubs/EH1 -EndpointType webhook -EventSubscriptionName EventSubscription1 -EventTtl {EventTtl} -IncludedEventType $includedEventTypes -MaxDeliveryAttempt {MaxDeliveryAttempt} -ResourceGroupName MyResourceGroup -TopicName Topic1
```

