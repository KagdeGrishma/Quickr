Tech Phantoms : Josemon Baby, Grishma Kagde, Yash Sowani

What The code does ?

Creating a system that makes it easier to transfer a URL,
text, or document from one device to another. There are 
several other solutions such as Google Drive and other 
cloud apps, but the main focus here is to eliminate the
requirement for creating an account, downloading their 
software, or maintaining sync for particular files or 
folders.

How to Compile and run the code?

Steps to setup the database and run the code on the local.

Changes in application.properties
-Change the url from host.docker.internal to localhost and set the respective mysql password.
-Change the ddl-auto property from none to create for creating the tables in the database.
-Run by clicking the green arrow in the QuickrApplication class.
-Revert the changes once the database and table are created and the system is running on the local.

Steps to check the Kubernetes functionalities for scaling

- minikube start

- Create a docker hub account

- create a jar file of your project

- mvn clean compile install

Create the kubernetes resource
- kubectl apply -f kubernetes.yml


Exposes the external IP directly to any
program running on the host operating system using the below mentioned command.
- minikube tunnel

Automatically viewing the dashboard of Kubernetes
- minikube dashboard


Video Link :
https://drive.google.com/file/d/17x9Ns-y7Loy2si9e4oc2GMqCSeg5tWhx/view

Private Gitlab Repository URL:
https://gitlab.com/greeshma.kagde37/quickr.git



