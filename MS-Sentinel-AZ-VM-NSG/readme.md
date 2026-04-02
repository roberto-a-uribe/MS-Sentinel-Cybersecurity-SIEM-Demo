## Objective 1 - Adjust Azure VM Network Security Group
In this scenario I will delete the default RDP port 3389 security rule then I will be creating a new MALICIOUS rule for RDP traffic to expose
interet traffic to VM.


![MS-Sentinel-AZ-VM-NSG](Azure-RUAIT-NSG-1.png)


![MS-Sentinel-AZ-VM-NSG](Azure-RUAIT-NSG-deleteRDP.png)

### Delete the default rule

![MS-Sentinel-AZ-VM-NSG](Azure-RUAIT-NSG-deleteRDP1.png)

### Add a new security rule - ALLOW ANY TRAFFIC

![MS-Sentinel-AZ-VM-NSG](Azure-RUAIT-NSG-add-rule.png)

![MS-Sentinel-AZ-VM-NSG](Azure-RUAIT-NSG-add-rule1.png)

![MS-Sentinel-AZ-VM-NSG](Azure-RUAIT-NSG-add-rule-test-malicious.png)
