<img width="1920" height="1080" alt="EC2 Instances(Jenkins,Nexus,Tomcat)" src="https://github.com/user-attachments/assets/ae58c1d9-880b-4e4b-9f42-4096971b9090" />
three running AWS EC2 instances used for a CI/CD pipeline:  
- Jenkins for CI  
- Nexus for artifact repository  
- Tomcat for application deployment 


<img width="1920" height="1080" alt="pipeline job creation" src="https://github.com/user-attachments/assets/af569367-9086-4943-928d-d010daba0c87" />

<img width="1920" height="1080" alt="Jenkins Pipeline Job Configuration  GitHub Source Checkout" src="https://github.com/user-attachments/assets/d119dd07-f6e5-41f1-ba9f-07942faf2606" />
Jenkins Pipeline job configuration where the pipeline script pulls source code from a GitHub repository using the git step in a declarative pipeline.

<img width="1920" height="1080" alt="GitHub Repository Checkout" src="https://github.com/user-attachments/assets/336842e6-2169-4013-b1e4-55c9abb9b557" />
Jenkins pipeline stage logs confirming a successful clone and checkout of source code from a GitHub repository during the CI build process.

<img width="1920" height="1080" alt="Maven Build" src="https://github.com/user-attachments/assets/97fe5f66-c5dd-4bf9-89ee-4890a98707bd" />
where source code is cloned from GitHub and built using Maven (mvn clean package) as part of the CI process.

<img width="1920" height="1080" alt="Console Output – Maven Build Execution" src="https://github.com/user-attachments/assets/117545f5-4609-47ea-a59b-3d4289da6ae0" />
This displays the Jenkins console output showing a successful Maven build (mvn clean package), where dependencies are downloaded and a WAR file is generated as part of the CI pipeline.

<img width="1920" height="1080" alt="Build, Nexus Upload   Tomcat Deployment" src="https://github.com/user-attachments/assets/545e9eb6-f502-4ced-8ee7-2cad001685ff" />
enkins declarative pipeline script that builds a Java application using Maven, uploads the generated WAR file to Nexus Repository Manager, and deploys it to an Apache Tomcat server automatically.





