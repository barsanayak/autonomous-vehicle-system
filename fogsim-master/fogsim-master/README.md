# fogsim
A Toolkit for Modeling and Simulation of Resource Management Techniques in Internet of Things, Edge and Fog Computing Environments


## How to run autonomous-vehicle-system ?

* Create a Java project in Eclipse. 
* Inside the project directory, initialize an empty Git repository with the following command
```
git init
```
* Add the Git repository of autonomous-vehicle-system as the `origin` remote.
```
git remote add origin https://github.com/barsanayak/autonomous-vehicle-system.git
```
* Pull the contents of the repository to your machine.
```
git pull origin master
```
* Include the JARs (except the CloudSim ones) to your Eclipse project.  
* Run the class "AutnomousVehicleSystem" as  Java Application
*On recieving the output, various required values can be used for analysis  


*Parameters and Configuration:  
  
1. For Cloud computing values , CLOUD = true  
   For Fog Computing values, CLOUD = false;  

2. To vary the number of vehicles, vary the following parameters  
	numOfFogDeviceArea   
	numOfVehiclesPerFogDeviceCoverage  
  
  ## Input Parameters    
  *Placed in #input# folder   
    
  ## Output Files     
  *Placed in #output# folder  
  
  # Analysis Results 
  The data and graphs are placed in #reults# folder
	

