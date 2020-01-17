### Example 1: This command gets the publishing profile in Ftp format for slot Slot001 pertaining to the Web App ContosoWebApp associated with the resource group Default-Web-WestUS
```powershell
PS C:\> Get-AzWebAppSlotPublishingProfile -Format WebDeploy -Name ContosoWebApp -OutputFile C:\Users\contoso\outputfile -ResourceGroupName Default-Web-WestUS -Slot slot001
```

