# DEVOPS-Java-Maven-Build-Job

In this task I have Run a Simple Java Maven Build Job in Jenkins

Project folder --> Java-maven-build-job/src/main/java/HelloWorld.java 

  | ---> Java-maven-build-job/pom.xml

.java file contains Program file.


pom.xml contains Maven project configuration file.


Jenkins Configuration --> manage jenkins --> Tools --> Maven Installations --> version 3.8.6 --> apply and save

jenkins --->Create a new Freestyle project --> source code management --> git --> Build steps ---> Invoke top-level Maven targets ---> goals --> clean package ,then save and build.



Console Output:
<img width="1895" height="1070" alt="image" src="https://github.com/user-attachments/assets/8f87ae01-f823-4290-babd-102a207f0fb2" />
