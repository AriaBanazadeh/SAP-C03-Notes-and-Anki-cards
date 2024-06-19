Cloud watch or CW is used for monitoring and logging purposes.

It has 3 parts, 

Cloudwatch -> Metrics (gathered from AWS, like CPU utilization)

Cloud watch Log -> Logging (Custom logs, etc)

Cloud watch EVents -> Events (If Log or f(Metric) then do some action, SMS or complex actions)

There can be different namespaces wihtin Cloud watch, each namespace 

Metrics are usually time ordered set of data points

Each data point has the (time sent, value, dimension it comes from )

so for exampel if Ec2-v1 has 30% cpu at this time it'll send (now, 30%, AWS resource details, AMI details)

The details that identify it are called the 'dimensions'