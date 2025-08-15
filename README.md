# DEVOPS-Java-Maven-Build-Job

In this task I have Run a Simple Java Maven Build Job in Jenkins

Project folder --> Java-maven-build-job/src/main/java/HelloWorld.java 

  | ---> Java-maven-build-job/pom.xml

.java file contains Program file.


pom.xml contains Maven project configuration file.


Jenkins Configuration --> manage jenkins --> Tools --> Maven Installations --> version 3.8.6 --> apply and save

jenkins --->Create a new Freestyle project --> source code management --> git --> Build steps ---> Invoke top-level Maven targets ---> goals --> clean package ,then save and build.


Java Output in console --- configure --> Add build step --> Execute shell --> java -cp target/hello-1.0.jar HelloWorld




Console Output:
<img width="1876" height="1068" alt="image" src="https://github.com/user-attachments/assets/82470684-7e40-4119-8263-eeab9683ef7b" />


