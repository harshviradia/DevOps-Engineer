TOOLS AND TECHNOLOGY


2.1 INTRODUCTION TO LINUX

•	Linux is a community of open-source Unix like operating systems that are based on the Linux Kernel. It is a free and open-source operating system and the source code can be modified and distributed to anyone commercially or noncommercially under the GNU General Public License. In this chapter we learned about basic commands, firewall management, process management.

2.2 DOCKER CONTAINER

●	Bridge Network

•	In terms of Docker, a bridge network uses a software bridge which allows containers connected to the same bridge network to communicate, while providing isolation from containers which are not connected to that bridge network. The Docker bridge driver automatically installs rules in the host machine so that containers on different bridge networks cannot communicate directly with each other.
•	In this task,we learned about how to create bridge network, how to attach container to network Bridge network,the communication of two containers inside the network.etc

2.3 INTRODUCTION TO CICD

•	A CI/CD pipeline automates your software delivery process. The pipeline builds code, runs tests (CI), and safely deploys a new version of the application (CD).


 
Fig 2.1 CICD 
2.4 CICD USING AWS CODEPIPELINE

•	AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin. With AWS CodePipeline, you only pay for what you use. There are no upfront fees or long-term commitments.
•	AWS Codepipeline consists the following components
•	AWS CodeCommit-It is secure,highly scalable,manged source control service,that hosts private git repositories.CodeCommit eliminates the need to manage your own source control system. It supports the standard git functionality.
•	AWS CodeBuild-It is fully managed continuous integration service that complies source code,runs tests,and produces software packages that are ready to deploy.With codebuild,you don’t need to provision,build your own servers.
•	AWS CodeDeploy- AWS CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

 
Fig 2.2 Codepipeline

2.5 HARDWARE REQUIREMENT
•	A Computer system with 
•	4 GB Ram
•	Windows OS
•	Software Requirements 
•	AWS Console

2.6 SOFTWARE REQUIREMENT
•	Docker
•	Github
•	GitLab
•	Linux OS	












TASK DESCRIPTION


3.1 INSTALLATION AND CONFIGURATION OF NGINX SERVER

●	I performed this task on Linux OS using virtual box.Here I installed nginx server in the linux os and changed its configuration in the nginx.conf file.The nginx server is running on port 80,which can be changed in the configuration file.Also the Document root can be changed from here.

Task 1
Task Description	Installation and configuration of nginx server
Trigger	Server keeps on running
Basic Path	/var/www/html

Post Condition	Welcome page
Output Screenshots	  
Table 3.1 Task1

3.2 STATIC WEBSITE HOSTING ON APACHE/NGINX

•	In this task,I hosted a static react based website.In this task, the source code was placed inside the document root of the nginx.ow we just need to start the nginx server and the task is done.We can check the website by using the curl command.Also if you are using a public IP,we can se the website by <public ip >:80.





Task 2
Task Description	Static website hosting on nginx
Trigger	Server keeps on running
Document root	/var/www/html
Config file	/etc/nginx/conf.d
Output Screenshots	
 
Table3.2 Task 2

3.3 STATIC WEBSITE HOSTING USING USR/DIR AS DOCUMENT ROOT

●	The task is same as the above one,we just need to change the document root inside the configuration and the task is done.
●	Hosting Php application on nginx server

Task 3
Task Description	Static website hosting on apache/nginx server using user dir as  document root
Trigger	Server keeps on running
Document root	/var/www/html
Config file	/etc/nginx/conf.d
Output Screenshots	
 
Table 3.2 Task3







3.4 BRIDGE NETWORK IN DOCKER CONTAINER

•	In this task, I created two containers ,one for php and other for database .Both the database and container must be in the same bridge network. Now, after creating the database we need to go inside the container and create a php file to connect to the database and to insert data into it. now we can check the data inserted by going inside the database container and checking the records.

Task 4
Task Description	Hosting Php application on nginx server
Trigger	Server keeps on running
	
Webserver	Nginx
Output Screenshots	
 
Table 3.4 Task 4

3.5 HOSTING A STATIC WEBSITE ON DOCKER CONTAINER

•	In this task first create a dockerfile related to your website.Now after Creating the dockerfile,we need to create the image of it and there after building that image will create container with the static website.




Task 5
Task Description	Bridge network in Docker Containers Bridge network in Docker Containers
Trigger	no
	
Container	Docker
Output Screenshots	
 
	
Table 3.5 Task5

3.6 WRITEFREELY APPLICATION DECOUPLED ARCHITECTURE ON DOCKER CONTAINER

•	Writefreely is a blogging application which has its own server and runs on it.In this decoupled architecture,there are in total 3 containers.one for application container,second for nginx server and third for database.










Task 6
Task Description	Hosting a static website on Docker Container
Trigger	No
	
Container	Docker
Output Screenshots	
 
Table 3.6 Task6
3.7 AWS CODEPIPELINE USING SOURCE AND DEPLOY

•	In this task,the main aim was to get introduce with workflow of CICD pipeline.i just created a pipeline and whenever a new change is commited, the pipeline gets executed.

Task 7
Task Description	AWS Codepipeline using source and deploy

Trigger	Commit in the repository
	
Target	S3 Bucket
Output Screenshots	

Table 3.7 Task 7

3.8 AWS CODEPIPELINE USING SOURCE,BUILD & DEPLOY

•	In this task,the main aim was to get introduce with workflow of CICD pipeline.i just created a pipeline and whenever a new change is commited, the pipeline gets executed.

 
LEARNING EXPERIENCES


4.1 KNOWLEDGE ACQUIRED/SKILLS LEARNT

●	This internship helped us to gain knowledge regarding Linux,Docker and CICD.The most important thing we learnt is the debugging skill.We also learnt how to approach a task defiantion and to implement it.

4.2 INDUSTRY PRACTICE ADAPTED
●	Coding ethics
●	Code review