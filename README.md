# aws-core-services


#### Count AZ with Powershell

```powershell
Import-Module AWSPowerShell.NetCore

AWSPowerShell.NetCore

$zones = Get-EC2AvailabilityZone -Filter @{ Name="state";Values="available" }
$zones.count
```
