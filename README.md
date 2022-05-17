# aws-core-services


#### Count AZ with Powershell

```powershell
Import-Module AWSPowerShell.NetCore

AWSPowerShell.NetCore

$zones = Get-EC2AvailabilityZone -Filter @{ Name="state";Values="available" }
$zones.count
```

### Launch Windows Machine via CLI

```
aws ec2 run-instances --image-id
```
