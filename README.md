# FHV_RESTful_Example
Reference RESTful Project for Intellij 

original project source:
https://www.jetbrains.com/help/idea/creating-and-running-your-first-restful-web-service.html


=> enable Glassfish 5.0
After installation, navigate to the Glassfish installation location, 
more specifically to its configuration directory: 


C:\<your_directory>\glassfish-5.0\glassfish\config


Add this line to the asenv.bat file: 


set AS_JAVA=C:\<your_jdk_directory>\Java\jdk1.8.<your_most_current_jdk_version>


Additionally, add this line to the asenv.conf file:


AS_JAVA=C:\<your_jdk_directory>\Java\jdk1.8.<your_most_current_jdk_version>


hint:
you might want to add the respective libraries to the project ...





