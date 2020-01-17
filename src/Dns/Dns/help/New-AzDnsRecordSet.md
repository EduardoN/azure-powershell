### Example 1: The New-AzDnsRecordSet cmdlet creates a new Domain Name System (DNS) record set with the specified name and type in the specified zone.
```powershell
PS C:\> New-AzDnsRecordSet -DnsRecords $Records -Metadata {Metadata} -Name * -RecordType A -Ttl <UInt32> -Zone $Zone
```

