# spring-boot-aws

creating a EC2 instance:
1. Choose AMI - Amazon Machine Image
2. choose instance type - Server micro
3. Configure instance - no of instance/n/w (VPC)/ subnet/ IAM roles
4. Add storage - size/ IOPS/ 
5. Add Tags
6. Configure security group - (type)SSH/(protocol) TCP/ (port range) 22/ (Source) anywhere or my IP 
7. Review

unix/linux commands:
1. create EC2 instance
whoami -> user name
sudo -i -> root directory
sudo yum install java-1.8.0-openjdk - install java 8
alternatives --config java -> configure java version 
2. create s3 bucket
create a bucket
upload or copy the jar.
Copy the jar url -> https://lokiaws.s3.amazonaws.com/spring-boot-aws-exe.jar
do wget https://lokiaws.s3.amazonaws.com/spring-boot-aws-exe.jar in the putty

install jar in putty
java -jar spring-boot-aws-exe.jar

ipaddress and access the application
ec2-3-238-114-163.compute-1.amazonaws.com:8080/
