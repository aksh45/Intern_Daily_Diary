# Intern_Daily_Diary


## Week 1 (Feb 2 2022 - Feb 9 2022)

There was an induction program by IT department , they gave us instructions on How to use company's laptop and how to configure zscaler products on it. After that there was a session by HR , she gave us brief introduction about company's policies then a course was assigned to us which contains information about company policies and some basic Engineering practices. Then there was a meeting with Manager and team. Manager introduced me to the entire team. A buddy was assigned to each intern. My buddy assigned me some internal product overview courses.

## Week 2 (Feb 10 2022 - Feb 17 2022)

Entire week was spend in completing the courses assigned by the HR and my buddy. The courses were all about the workflow of the product , how product works at its core and Legal ethics of the company. Since I have signed an NDA with the company so I can't share much information

## Week 3 (Feb 18 2022 - Feb 25 2022)

In the week 3 our company planned to give us internal training on fundamentals of subjects Like Linux, Networking and AWS. Initially in the 1st week of internal training  topics like processes , liniux shell and types , read and echo commands, bash scripting were taught. The tutor gave us daily practice assignments and at the end of the week a Mile stone assignment was given. Along with these learning sessions there was a biweekly meeting with buddy.

## Week 4 (Feb 26 2022 - March 5 2022)

In the week4 we were taught about fundamentals of Networking like physical security , internet security, wireless security , basic commands like ping, ifconfig, nmap were taught. In the same week my buddy assigned me a course to understand the working of Zscaler internet access.

## Week 5 (March 6 2022 - March 13 2022)

Networking training was stll going on , our guide taught us password recovery techniques, basics of wireshark. Parallely I was working on the course which my buddy assigned me , this course was all about the system design of the product, 50% of the course was completed.

## Week 6 (March 14 2022 - March 21 2022)

Static and dynamic routing, Router configuration , CIDR was taught in this week. Zscaler Internet Access course was completed by me , I submitted the report to my buddy.

## Week 7 (March 22 2022 - March 29 2022)

This week was all about AWS. AWS EC2, S3, VPC , Network ACLs, Security groups, AWS VPN , AWS RDS were taught to us . The guide provided us 50$ worth of credits for hands on practice . We created AWS EC2 instances for linux, windows, RDS instances of mysql, mariadb  and S3 buckets of different tiers with and without public access .


## Week 8 (March 30 2022 - April 6 2022)

An Milestone assesment was taken for both Networking and AWS was taken by the company on Tuesday and one day was given for preparartion. An task was assigned by manger to Automate the OKTA SSO Login. I started doing my study on SSO , How they work. I tried to search for login workflow in the documentation of OKTA but the documentation was not that great.

## Week 9 (April 7 2022 - April 14 2022)

Tried to reverse Engineer OKTA SSO Login and tried to replicate all the API calls that were made using Postman and I was successfully able to generate a session token through which we can login to any app present in the Okta dashboard. My next task was to hit these API using python script and automate the complete process. 

## Week 10 (April 15 2022 - April 22 2022)

Worked On the python script to automate OKTA SSO for Zscaler product. Sent the version one to the project guide. He suggested to look over the automation for google authenticator, then I added support for automatically generating the OTP using totp algo. At the end of the week there was a presentation with all the managers and team, the team approved the script and further I was assigned the task to pick the data for new cloud creation from jira ticket and create that cloud in zscm portal. My okta SSO automation was one small part for this project.

## Week 11 (April 23 2022 - April 30 2022)

Explored the jira tickets and tried to create the cloud manually in the portal, the portal was completely new to me so I contacted Ketan , he provided me the course on ZSCM portal. Rest of the week was used in understanding the zscm workflow and how the basic architecture works.

## Week 12 (May 1 2022 - May 8 2022)

Used Jira Webhook and sent all jira tickets releated to modification in existing cloud and creation of new clouds to a python server, so a webhook reciever i.e python server will recieve a POST request , after that it will go into approval queue and manager will approve the request. This part of the code was working fine , so the next task is to impliment what will happen with ticket after approval.

## Week 13 (May 9 2022 - May 16 2022)

The jira ticket created by support team usually contains which are necessary for creation or deletion in cloud , so I wrote an automation function which performs all the tasks which are done manually. providing much details of the conversion function is not possible. Conversion function was working properly , now the task left is to  aggregate the conversion function and the flask server code.

## Week 14 (May 17 2022t - May 24 2022)

Aggregated the conversion function and flask server, now when the request will be approved by the manager , it will call the conversion function and do creation or deletion action on zscm portal. At end to summarize the project was to use jira webhooks and send a request to flask server whenever a ticket is created to delete or update the cloud portal of the company, after the request reaches to the server it wait in queue until it get approved, after that it performs the desired action on the cloud portal.

## Week 15 (May 25 2022 - June 1 2022)

Super cloud task assigned to me  was finished. I gave the presentation to the managers. After 2 days a new task was assigned to me , the task was that zscaler have about 1000 domains and all the domains have their ssl certificates my task was to write a script to check whether these certificates have expired or not , if the certificate is expired then send an alert to the Devops team.

## Week 16 (June 2 2022 - june 7 2022)

I started to work on the task assigned to me in previous week , I explored many python libraries to fetch the ssl certificate then I cam across ssl module which can be used to fetch the certificate from the server. After completing my part I submitted the script to my senior.
## Week 17 (June 8 2022 - June 15 2022 )

My manager asked me to learn about AWS , a 2 weeks specialisation course was provided by him 1st course of the specialisation was AWS management, this course provided me details about different AWS management tools avilable like GUI , command line line tools , third party tools like cloudaware. It also taught me about cloudformation, resource tagging, AWS for Visual studio code , How to use some sample templates of cloud formation, another course in the specialisation was about s3 buckets.

## Week 18 (June 16 - June 19 2022)

This entire week was spent in completing the AWS course, I learned about S3 security , what are bucket policies , ACLs, S3 object locking , S3 Object encryption. Another course was about VPC Management & peering, this course gave me information on what VPCs are , How can I create my own VPC, what are elastic IP address, VPC peering and AWS VPN solutions also I learned about different tiers of EC2 instances and how to deploy an EC2 Instance.

