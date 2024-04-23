# Lab-How-To-Create-a-CloudWatch-Alarm-for-CPU-Utilization

## 1. Create EC2 for Amazon Linux

![alt text](image.png)

## 2. Create Cloudwatch Alarm

- In the AWS Management Console, type `cloudwatch` into the search box, and then select the `CloudWatch` service.

![alt text](image-1.png)

- Click `All alarms`

![alt text](image-2.png)

- Click `Create alarm`

![alt text](image-3.png)

- Click `Select metric` 

![alt text](image-4.png)

- Click `EC2`

![alt text](image-5.png)

- Click `Per-Instance Metrics`

![alt text](image-6.png)

- Select `Cloudwatch Lab` and click `Create alarm`

![alt text](image-7.png)

- Set Period based on your need

![alt text](image-8.png)

- Select `Greater/Equal` and Write `80` and then Click `Next`

![alt text](image-9.png)

- Select `Create new topic` , Write topic name and your email then click `Next`

![alt text](image-11.png)

- Write `CPU High Usage Alert` and click `Next` then click `Create alarm`

![alt text](image-12.png)

## Install stress application at EC2

![alt text](image-13.png)