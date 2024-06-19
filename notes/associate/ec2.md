EC2 stands for **Elastic computer cloud**.

Each EC2 belongs to one availaibitly zone or in otherwords one subenet of a VPC. 

It's a **private service** by default so it is inside of a VPC.

That means it's AZ resilient, if the availability zone fails it'll fail with it.


Each computer in EC2 is composed of CPU, Memory (RAM), Disk (Operating system + files (EBS)), Networking

COST is on-demand billing. Meaning that you pay per hour or per second for the things you use. 

EC2 instances can have 3 stages

Running      Stopped     Terminated 

In running you get cost for all 4 of the CPU, Memory, Disk, and networking.

In stopped you only get charged for the Disk.

In terminated you don't get charged for anything.

AMI: Basically an image to creat ethe virtual machine (EC2 instance). It conatins infrormation on poerpating system, the volume mapping and other things. 

