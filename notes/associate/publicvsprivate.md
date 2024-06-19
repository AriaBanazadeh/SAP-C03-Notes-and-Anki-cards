You can break down AWS into 2 parts. 

1- Public part: Includes Things like S3. They can be accessed by the internet directly. They have a public IP.

2- Private part: Composed of VPC (Virtual private cloud), these are isolated networks. 
                They can contain resources

                These private parts don't have a public IP by default (so can't be accessed by tthe internet)
                But they can be configured using internet gateway to get a public ip and hence be accessed or access internet (example of an EC2 instance in a VPC connecting to google )


