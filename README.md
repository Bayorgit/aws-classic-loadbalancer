# aws-classic-loadbalancer : every code works right but it came up with this lone error about the provisioner. ****Bayo remember to figure this out****
 with null_resource.name,
│   on nullresource-provisioners.tf line 26, in resource "null_resource" "name":
│   26:   provisioner "local-exec" {
│
│ Error running command 'echo VPC created on `date` and VPC ID: vpc-0307f50072afcd0ac >> creation-time-vpc-id.txt': exec: "cmd": executable file  
│ not found in %PATH%. Output:
╵i added "if failure=continue" to the provisioner
