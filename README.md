# OneClickAutomation

Exercise-1.

As per given scenario I have below solution which can automate the various process which are being done manually in organization.

Version Control stage-->

Developers will be writting the code and as soon as they commit the code it will go in version control stage.In this stage we can manage the code written by developers.
Vaious tools can be used to manage the source code for example git is one of the tool.

Continuous Integration-->

When any developers commit the code and that code is merged with master branch then Integration tool (Jenkins) can be used to create a build and after that we can test our code in virtualized environment.

Continuous Testing-->

In this stage we can automate the test by writting a selenium script then run it through Jenkins in virtualized environment.
If test fails we stop here and send back the issues to develeper and again the above process will be followed.
If test passes we move ahaed and deploy it.

Continuous Deployment-->

In continuous deployment we have two parts-->
1. Configuration management

We have different configuration tools for the configuration management.
Chef
Puppet
Ansible

2. Containerization

Docker is tool through which we can run as much as containers by creating the images. Containers are the run time instance of the images and Images are the collection of applications and their dependencies.

Continuous Monitoring-->

We have different tools such as Nagios through which we can monitor the applications. It ensures that application is performing as desired and the environment is stable.
If we get any issues the we will again go to develeopers and again whole process will be followed continuously.



Above process will be followed continuously untill we get all issue resolved and we are goood to deliver the application in production.
