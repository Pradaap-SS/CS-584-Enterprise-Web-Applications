How to install Tomcat.

1. Go to the website http://tomcat.apache.org/.
2. Click on Download Tomcat 9 on the left navigation bar.
3. Under Tomcat 9 Software Downloads > 9.0.52 > Click on the zip file and save into your directory.
4. Unzip the file and place it in C:\ drive.
5. Unzip the Tutorial_1 file and paste the Tutorial_1 folder inside C:\apache-tomcat-9.0.52\webapps


Environment set-up

Open the command prompt and run the below script.

set JAVA_HOME=C:\Program Files\Java\jdk1.8.0_261

set PATH="C:\Program Files\Java\jdk1.8.0_261\bin";%PATH%

set CLASSPATH=.;C:\apache-tomcat-9.0.52\lib\servlet-api.jar;C:\apache-tomcat-9.0.52\lib\jsp-api.jar;C:\apache-tomcat-9.0.52\lib\el-api.jar;C:\apache-tomcat-9.0.52\lib\commons-beanutils-1.8.3.jar;C:\apache-tomcat-9.0.52\mongo-java-driver-3.1.0.jar;C:\apache-tomcat-9.0.52\lib\gson-2.3.1.jar

set ANT_HOME=C:\apache-tomcat-9.0.52

set TOMCAT_HOME=C:\apache-tomcat-9.0.52

set CATALINA_HOME=C:\apache-tomcat-9.0.52

In the command prompt change the directory, using the command "cd C:\apache-tomcat-9.0.52\bin"

Type "startup.bat" and press Enter to start the Apache Tomcat.

Go to your browser and type localhost:8080 and press Enter.


