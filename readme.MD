# Terraform AWS ec2

## Arguments
ami_id - (mandatory), user must provide AMI ID .This is in string format
instance_type - (optional), default is t3.micro
security_group_ids - (mandatory)


## outputs

public_ip - public_ip of the instance created
private_ip - private_ip of the instance created
instance_id - instance ID of instance created 