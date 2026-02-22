<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Cloud Security with AWS IAM

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-security-iam)

**Author:** Tayllore Johnson  
**Email:** taydj5@gmail.com

---



---

## Introducing Today's Project!

### Project overview

In this project, I demonstrated how to use AWS IAM to control access and permission settings within an AWS account. We completed this project to learn cloud security from the absolute foundations, since every company must carefully manage access permissions. There are entire roles called IAM Engineers that focus on the exact skills practiced in this project.

### Tools and concepts

IAM user and group creation, attaching policies to users and groups, and managing permissions to control access to AWS resources.

### Project reflection

This project took me approximately 20 minutes to complete. The most rewarding part was gaining hands on experience creating IAM users and groups and attaching policies to manage permissions effectively in AWS.

---

## Tags

### What I did in this step

In this step, we launched two EC2 instances because we needed to boost NextWork's computing power. We are expecting more users and increased website traffic over the summer break.

### Understanding tags

### My tag configuration

![Image](http://learn.nextwork.org/satisfied_vermilion_vibrant_porcupine/uploads/aws-security-iam_2e0e5a5d)

---

## IAM Policies

### What I did in this step

In this step, we used IAM policies to control the access level of a new NextWork intern. The intern should have access to the development environment and its EC2 instance, but not the production environment.

### Understanding IAM policies

IAM policies are rules that determine who can do what within an AWS account. In this project, we created a policy using JSON to control who has access to the production environment instance.

### The policy I set up

For this project, I set up a custom policy using JSON to restrict access appropriately.

### Policy effect

### Understanding Effect, Action, and Resource

---

## My JSON Policy

![Image](http://learn.nextwork.org/satisfied_vermilion_vibrant_porcupine/uploads/aws-security-iam_1c864649)

---

## Account Alias

### What I did in this step

In this step, we set up an account alias, which acts as a nickname for the AWS account console login. This makes it simpler and more user friendly for IAM users to sign in.

### Understanding account aliases

### Setting up my account alias

![Image](http://learn.nextwork.org/satisfied_vermilion_vibrant_porcupine/uploads/aws-security-iam_0eb4439b)

---

## IAM Users and User Groups

### What I did in this step

In this step, I set up a dedicated IAM group for all NextWork interns so I could manage intern permissions from one centralized location.

I also created a dedicated IAM user for the new intern so they would have credentials to log in.

### Understanding user groups

IAM user groups are collections of IAM users that share the same permissions. Instead of assigning permissions to each user individually, policies are attached to the group, and all users in that group inherit those permissions.

### Attaching policies to user groups

Attaching a policy to an IAM user group grants the permissions defined in that policy to all users within the group. Any user added to the group automatically inherits those permissions, making access management easier and more consistent.

### Understanding IAM users

---

## Logging in as an IAM User

### Sharing sign-in details

### Observations from the IAM user dashboard

After logging in as the IAM user, I noticed that access to many AWS services was restricted. This was expected and confirmed that the policy attached to the nextwork dev group was working correctly.

![Image](http://learn.nextwork.org/satisfied_vermilion_vibrant_porcupine/uploads/aws-security-iam_6f2ab446)

---

## Testing IAM Policies

### What I did in this step

In this step, I tested the intern’s access to both the production and development EC2 instances. This was done to ensure the account creation process and permission settings were configured correctly. 

### Testing policy actions

### Stopping the production instance

![Image](http://learn.nextwork.org/satisfied_vermilion_vibrant_porcupine/uploads/aws-security-iam_0e7a9d6a)

### Stopping the development instance

![Image](http://learn.nextwork.org/satisfied_vermilion_vibrant_porcupine/uploads/aws-security-iam_1811801c)

---

## IAM Policy Simulator

### Understanding the IAM Policy Simulator

### How I used the simulator

---

---
