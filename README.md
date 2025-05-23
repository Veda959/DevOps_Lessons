
# DevOps_Lessons (My Personal Repo on DevOps) 

# What is DevOps ?
DevOps is a culture that helps organizations to improve the ability to deliver the applications efficiently.
Not only delivery of the applications, here we have more in a shell to know about devops culture:
1. Improving Delivery
2. Automation
3. Quality
5. Monitoring
5. Testing

So, Now the actual definition is " DevOps is a process of improving the delivering of applications, by ensuring there is proper automation, ensured quality in place, ensured set up of monitoring and ensured a set up of continuous testing.
# Industry Definition of DevOps
DevOps isn’t a product or a tool — it’s a culture, practice, and mindset that emerged from the real-world need for better collaboration between software development and IT operations.
# DevOps Model (Modern & Automation focused)
🤝 Combines Development + Operations
1. Continuous Integration (CI)
2. Continuous Delivery (CD)
3. Automation of testing, deployment, monitoring
   
✅ Pros:
1. Faster delivery.
2. Automation reduces errors.
3. Continuous feedback and improvement.
# Virtual Machines
















# Creating Resources/Virtual Machines through automation:

Why we use Automation? - To improve efficency by reducing time and increasing quality
To create a hundreds of resources - we use AWS EC2 API for the sake of efficiency and error free.
# AWS EC2 API 
What is Automation ? - It is a Scripted format of what we do manually, it is more useful when we have more number of a task to do.
When we need to create hundred of EC2 Instances, the better way to do it is automate through script.
Every service in the AWS have its own API, basically API's are "Request and Response" structures. The main components to be checked are:
1. Validation - Whether the API request is valid or not
2. Authentication - Whether the request API has access to the AWS console or not.?
3. Authorization - Wheteher the requested API is authorized to do that particular task or service to do anything (Like creating EC2 instances, the person should have access to the EC2 service).

# Interview Question - What tool do you use to for the automation of infrastructure in your organization ? 

Automation is basically done by script, First of all, what is this script actually and what are different scripting services available ?
We can choose any of the following scripting services based on our organization requirement
1. AWS CLI (AWS Command Line Interface)
2. AWS API (AWS Application Program Interface) - If we know a programming language we can write a better API to create the infrastructure (Like REST API's). For Python, we use BOTO3 module and write API to talk to AWS EC2 API to create "1 to n" Instances through Automation.
3. AWS CFT (AWS Cloud Formation Template)
4. Terraform (Open Source Infrastructure as Code tool by "HashiCorp") - If we are using "Hybrid Cloud Model", Terraform is the best choice to automate infrastructure among the different cloud platforms.
5. AWS CDK (AWS Cloud Development Kit)


# Interview Question - What is a kernel in Operating System ?
Operating System - OS is nothing but cascading the requests between Hardware and Software, but actually who takes this responsibility ? A component, that component is called - KERNEL
Kernel - Kernel is the heart of the Operating System. Kernel is like a chip, that establishes the communication between Hardware and Software.
There are 4 important aspects of the Kernel:
1. Device Management
2. Memory Management
3. Process Management
4. Handles System Calls
![image](https://github.com/user-attachments/assets/6c717e9c-6194-4011-aa10-16847262fd5b)

# LINUX Operating System:
This is a Light Weight Operating System which is:
1. Free
2. Open Source
3. Secure
4. Distributions - There are many distributions out here in the market where some are produces by vendors like (RedHat, Debian, Ubuntu, CentOs)
5. Fast

# Linux Commands:
1. mkdir
2. pwd
3. cd
4. cd ..
5. cd /
6. touch
7. rm
8. rm -f
9. mv
10. cp
11. cat
12. grep
13. free -g/ free -m - To check the memory available
14. nproc - To check how many CPU's are available
15. df -h - To check how much disc size is available
16. Top
17. ps -ef
18. ps -aux

# Interview Question - What is the command that you use to manage Memory, CPU or look in to it ?
"TOP" Command - Using this command, we can view the Memory, CPU, Tasks that are available, running, sleeping, from how much time the server is up end and every other details.
Individually also we can check the Memory and CPU using "free/ free -g/ free -m" and "nproc" respectively. To check all at once "TOP" is the best command.

# NETWORKING:
The Most important components in this networking are:
1. IP Address
2. VPC
3. CIDR Range
4. Subnet (Private & Public)
5. Ports

![common-network-ports-cheat-sheet-1232x1536](https://github.com/user-attachments/assets/02ec3c89-9900-4f26-a135-343b18a6102d)

6. OSI Model

# Version Control Management (or) Source Code Management (Git or GitHub)

The Most popular Older Version control systems are (CVS[Concurrent version Systems] and SVN[Subversion]) - These are "Centralized Versioning Systems"
Now-a-days "Git/GitHub" became more popular. - Git is "Distributed Versioning System"
Main Components to understand are:
1. Sharing of Data
2. Versioning

# Interview Question - What is the Difference between Centralized and Distributed Versioning Systems ?



