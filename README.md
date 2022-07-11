<h1>TOOLS AND TECHNOLOGY</h1>


<h2>2.1 INTRODUCTION TO LINUX</h2>

•	Linux is a community of open-source Unix like operating systems that are based on the Linux Kernel. It is a free and open-source operating system and the source code can be modified and distributed to anyone commercially or noncommercially under the GNU General Public License. In this chapter we learned about basic commands, firewall management, process management.

<h2>2.2 DOCKER CONTAINER</h2>

●	Bridge Network<br>

•	In terms of Docker, a bridge network uses a software bridge which allows containers connected to the same bridge network to communicate, while providing isolation from containers which are not connected to that bridge network. The Docker bridge driver automatically installs rules in the host machine so that containers on different bridge networks cannot communicate directly with each other.<br>
•	In this task,we learned about how to create bridge network, how to attach container to network Bridge network,the communication of two containers inside the network.etc<br>

<h2>2.3 INTRODUCTION TO CICD</h2>

•	A CI/CD pipeline automates your software delivery process. The pipeline builds code, runs tests (CI), and safely deploys a new version of the application (CD).<br>

![image](https://user-images.githubusercontent.com/60308162/178236813-5b0f444e-49b3-46dd-8d2b-12a6080f79d6.png)

 
<center>Fig 2.1 CICD</center> 
<h2>2.4 CICD USING AWS CODEPIPELINE</h2>

•	AWS CodePipeline is a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates. CodePipeline automates the build, test, and deploy phases of your release process every time there is a code change, based on the release model you define. This enables you to rapidly and reliably deliver features and updates. You can easily integrate AWS CodePipeline with third-party services such as GitHub or with your own custom plugin. With AWS CodePipeline, you only pay for what you use. There are no upfront fees or long-term commitments.<br>
•	AWS Codepipeline consists the following components<br>
•	AWS CodeCommit-It is secure,highly scalable,manged source control service,that hosts private git repositories.CodeCommit eliminates the need to manage your own source control system. It supports the standard git functionality.<br>
•	AWS CodeBuild-It is fully managed continuous integration service that complies source code,runs tests,and produces software packages that are ready to deploy.With codebuild,you don’t need to provision,build your own servers.<br>
•	AWS CodeDeploy- AWS CodeDeploy is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.<br>

![image](https://user-images.githubusercontent.com/60308162/178236885-fcee3615-c5cf-4df3-b91d-c83260ebc5a0.png)


<center>Fig 2.2 Codepipeline</center>

<h2>2.5 HARDWARE REQUIREMENT</h2>
•	A Computer system with <br>
•	4 GB Ram<br>
•	Windows OS<br>
•	Software Requirements<br> 
•	AWS Console<br>

<h2>2.6 SOFTWARE REQUIREMENT</h2>
•	Docker<br>
•	Github<br>
•	GitLab<br>
•	Linux OS<br>	












<h1>TASK DESCRIPTION</h1>


<h2>3.1 INSTALLATION AND CONFIGURATION OF NGINX SERVER</h2>

●	I performed this task on Linux OS using virtual box.Here I installed nginx server in the linux os and changed its configuration in the nginx.conf file.The nginx server is running on port 80,which can be changed in the configuration file.Also the Document root can be changed from here.<br>

![image](https://user-images.githubusercontent.com/60308162/178238788-69c0883c-ef65-46c5-8b14-1708c278722d.png)


<h2>3.2 STATIC WEBSITE HOSTING ON APACHE/NGINX</h2>

•	In this task,I hosted a static react based website.In this task, the source code was placed inside the document root of the nginx.ow we just need to start the nginx server and the task is done.We can check the website by using the curl command.Also if you are using a public IP,we can se the website by <public ip >:80.<br>





![image](https://user-images.githubusercontent.com/60308162/178238879-ee69c796-d536-456d-b83d-0cb710590920.png)

<h2>3.3 STATIC WEBSITE HOSTING USING USR/DIR AS DOCUMENT ROOT</h2>

●	The task is same as the above one,we just need to change the document root inside the configuration and the task is done.<br>
●	Hosting Php application on nginx server<br>

![image](https://user-images.githubusercontent.com/60308162/178238980-549168b8-b318-41eb-811c-29c3e32d2cd4.png)



<h2>3.4 BRIDGE NETWORK IN DOCKER CONTAINER</h2>

•	In this task, I created two containers ,one for php and other for database .Both the database and container must be in the same bridge network. Now, after creating the database we need to go inside the container and create a php file to connect to the database and to insert data into it. now we can check the data inserted by going inside the database container and checking the records.<br>

![image](https://user-images.githubusercontent.com/60308162/178239079-2cb7cd6d-192a-46a4-a3b8-429ec22810df.png)

<h2>3.5 HOSTING A STATIC WEBSITE ON DOCKER CONTAINER</h2>

•	In this task first create a dockerfile related to your website.Now after Creating the dockerfile,we need to create the image of it and there after building that image will create container with the static website.<br>




![image](https://user-images.githubusercontent.com/60308162/178239349-e5d46530-bc00-4cd9-9267-b2995efb842a.png)

3.6 WRITEFREELY APPLICATION DECOUPLED ARCHITECTURE ON DOCKER CONTAINER

•	Writefreely is a blogging application which has its own server and runs on it.In this decoupled architecture,there are in total 3 containers.one for application container,second for nginx server and third for database.










![image](https://user-images.githubusercontent.com/60308162/178239443-de05882a-044a-4d2f-bef7-8087277d6442.png)

<h2>3.7 AWS CODEPIPELINE USING SOURCE AND DEPLOY</h2>

•	In this task,the main aim was to get introduce with workflow of CICD pipeline.i just created a pipeline and whenever a new change is commited, the pipeline gets executed.<br>

![image](https://user-images.githubusercontent.com/60308162/178239577-c4f8879a-c3aa-47db-a473-0acc175dab39.png)

<h2>3.8 AWS CODEPIPELINE USING SOURCE,BUILD & DEPLOY</h2>

•	In this task,the main aim was to get introduce with workflow of CICD pipeline.i just created a pipeline and whenever a new change is commited, the pipeline gets executed.<br>

 
<h1>LEARNING EXPERIENCES</h1>


<h2>4.1 KNOWLEDGE ACQUIRED/SKILLS LEARNT</h2>

●	This internship helped us to gain knowledge regarding Linux,Docker and CICD.The most important thing we learnt is the debugging skill.We also learnt how to approach a task defiantion and to implement it.<br>

<h2>4.2 INDUSTRY PRACTICE ADAPTED</h2>
●	Coding ethics<br>
●	Code review<br>
