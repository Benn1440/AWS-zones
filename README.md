# Amazon Web Services Availability Zones

Availability Zones in Cloud computing allows for inexpensive, low-latency network connectivity to other Availability Zones in the same AWS Region.
allowing organizations to have their services readily availably to their users in real time.
Meaning that AZ are engineered to be isolated from failures if other Availability Zones experience downtime of any sort.

Reference: https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html

# Project Scope

In this project, Two(2) websites were hosted in two different AZs, to ensure they are availaible at all time.

![EC2-instances](https://github.com/Benn1440/AWS-zones/assets/67696393/4c53766c-0066-420d-a487-a59c56044c56)

# User Data were inputed at the point of Instance creation.

This user data were passed into the instance, and they can be used to perform common automated configuration tasks and even run scripts after the instance starts.

# Image of the site running in the first instance in AWS

http://ec2-3-239-222-13.compute-1.amazonaws.com/

![instance 1](https://github.com/Benn1440/AWS-zones/assets/67696393/27ab0323-add0-44b8-a47b-e955e88d7836)

# Image of the site running in the second instance in a different AZ in AWS

http://ec2-3-93-246-108.compute-1.amazonaws.com/

![Instance 2](https://github.com/Benn1440/AWS-zones/assets/67696393/5ac199d6-b0ca-4cd7-8568-a574f0eeb996)

# In Conclusion

An Availability Zone (AZ) is one or more discrete data centers with redundant power, networking, and connectivity in an AWS Region. AZs give customers the ability to operate production applications and databases that are more highly available, fault tolerant, and scalable than would be possible from a single data center. All AZs in an AWS Region are interconnected with high-bandwidth, low-latency networking, over fully redundant, dedicated metro fiber providing high-throughput, low-latency networking between AZs. All traffic between AZs is encrypted. The network performance is sufficient to accomplish synchronous replication between AZs. AZs make partitioning applications for high availability easy. If an application is partitioned across AZs, companies are better isolated and protected from issues such as power outages, lightning strikes, tornadoes, earthquakes, and more. AZs are physically separated by a meaningful distance, many kilometers, from any other AZ, although all are within 100 km (60 miles) of each other.

Reference: https://aws.amazon.com/about-aws/global-infrastructure/regions_az/

# N.B: Running Instances would be Terminated to avoid Incurring cost
