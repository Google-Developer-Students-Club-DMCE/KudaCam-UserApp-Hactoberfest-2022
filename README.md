<<<<<<< HEAD
=======
<<<<<<< HEAD
>>>>>>> 98b5b7a (base commit)
# KudaCam-UserApp-Hactoberfest-2022


# Table of contents
1. [Introduction ](#kt0)
2. [WorkFlow of the Project](#kt1)
3. [Scope of the Study](#kt2)
4. [Proposed System ](#kt3)
5. [System Requirement ](#kt4)
6. [Getting Started](#kt5)
7. [References](#kt6)

<div id='kt0'>

## Introduction 
Municipal solid waste (MSW) is one of the important challenges to the environment. Municipalities; generally are responsible for waste management. They have to provide an effective and efficient system to the inhabitants. Nevertheless, they are; often; facing many problems beyond the ability of the municipal authority to handle the MSW. This is essentially due to financial resources, lack of organization and complexity . 

Without a doubt, the future lies in mobile applications. The new trends in digital and mobile developments mark a new era that influences human behavior and global governance. Mobile applications play an important role in many application areas such as industry, home, environment and health. This approach can be applied in the field of solid waste management to improve the way it works nowadays.

Our motivations come from the importance of improving the Solid waste collection management process using mobile technology by offering a mobile model matching with the new solid waste collection management challenge.


<div id='kt1'>

## WorkFlow of the Project

![Kudaflow](https://user-images.githubusercontent.com/83578700/196770292-2c4c297c-a205-49a2-9e02-e541a666d66e.png)

So a Technical solution for the management of solid wastes by providing visibility on city sanitation, route planning for garbage collection, resource optimization, air quality measurements, visibility of bins in order to maximize the waste collection. 

In the Current Case Scenario, the mechanism used by the Government Bodies to clean up Solid waste highly relies on finding out the concerned spots. And thus it becomes a tedious process for the workers. 

In this process most of the time workers do not find out the spots they have allotted or the spots that are complained by the user and hence this cause the solid waste remains uncollected in the area, increase in this waste harms the city sanitation and accordingly have many consequences. 

<div id='kt2'>

## Scope of the Study

This study helps us:
To bring out a model that will be a benefit to the community by providing a well defined approach that can regularly maintain the flow of solid waste Collection ?

To connect common Public users to the  workers  in charge of solid waste collection management and hence enhancing the current working mechanism 

To have waste collectors optimize the waste collection route, hence a reduction in the cost of waste collection.
To enable the Municipality to improve the quality of data on which making decisions is based on the annual waste budget.
To retrieve a well defined data of Users/Workers along with the impact the system had on the Air quality Index and how it helped to minimize the harmful effect on the environment 

<div id='kt3'>

## Proposed System

Inside of this section, we present the proposed model that is  a mobile application that is going to belong to solid waste collection management. We described the model using modeling language. Design model happens to be an existing object-based picture that represents the system or inside of another way, it has the ability to exist as defined during the same time as the means to describe an existing system’s implementation as well as source code inside of an existing diagrammatical fashion. In this model we are developing a model based on the current existing municipal process. 

We are looking forward to developing a technical solution for solid waste collection. in this model we are about to develop web and android for admin and user i.e public and workers. In our system we have four actors viz. admin, contractor, public, workers. Admins are the municipal officials that have assigned duties for sanitary inspection. contractors are the contract based workers appointed on the approval of admin. The public and workers are the main users of our systems. So let's understand the system in detail. First of all our system is divided in two parts viz. web and android application. 

Let's discuss each in detail.


* Web application:

web application is a type of portal to be used by municipal officials for registration of the workers, contract workers and volunteers. Using this portal admin or municipal officials will register workers and provide them with their login credential which will be later used by the workers for login into our system. Along with this, the admin will allot areas to the worker and keep records of the allotted area, also the admin will keep track of work done by the worker using the feedback given by the user through the pic given by the worker after the completion of work. This will help in tracking whether the complaints are resolved or not this provides the important validation to our system. Also admin can keep track of statistical information of total waste generation, AQI of locality. a web application can be used by a contractor approved by admin for adding contract based workers and keeping track of complaints. along with this web portal will be used to keep detailed information of AQI, statistical data of collection of garbage, and complaints registered and resolved.


* Android Application : 

Android applications are the main part of our system so to avoid crashing and complicating UI, we have divided it into two parts i.e. for public and worker. For the public, the public has to register and login into our system through which they can access our system which has various options like uploading complaints, community tab, event tab and self profile. For uploading complaints using the tab, users have to give permission for location and camera for clicking real time images of garbage. Through the community tab users can upload pictures of their contribution in “Swachh Bharat Abhiyan” .

 Through the event tab users can create events for cleaning particular beaches, roads etc. another important part in user application is location of garbage collectors or bins that will be nearby to them. Now let's come to an application  that is going to be used by workers. workers have to login to use our application. Workers have to use credentials that will be given by admin or municipal officials for login. After login, workers can see the map which will show the location and route map of complaints and garbage collectors or bins. workers will get notification of the complaints that are registered nearby. 

Once notified, the worker has to go to the location through the shortest possible path given by map and then claim the complaint within the time. Once a claimed complaint worker has to resolve the complaint and then click and upload a pic which will then be notified to the user for feedback which is in turn validation of workers work. 

In case a worker is busy resolving a complaint and receives another complaint, the complaint will be forwarded to another worker nearby. and hence work will be divided and can be completed as soon as possible. This record of every worker's claim will be kept by the municipal corporation through our website. 


<div id='kt4'>

## System Requirements 

##	Hardware Requirement

###	Laptop or PC

•	MacOS Sierra and above (If Mac setup is required)

•	Windows 7 or higher

•	I3 processor system or higher

•	4 GB RAM or higher

•	100 GB ROM or higher


###	Android Phone (6.0 and above)

###	iPhone (iOS 9 and above) (If iOS version needs to be checked)

##	Software Requirement

•	[Android Studio with Flutter Plugin](https://link-url-here.org)

• [Flutter SDK Download](https://docs.flutter.dev/get-started/install)

•	XCode (Latest version) (If iOS version needs to be checked on Mac)

<div id='kt5'>

## Getting Started

1. Fork& Clone the repository
2. Open repository in Android studio
3. Run command 'flutter pub get' at root of the structure
4. Create a New branch by the Command git checkout -b "branchname"
5. Code in! and add your code with git add. 
6. Commit the code with git commit -m  "anytext"
7. Push the code with git push origin "branchname"

<div id='kt6'>

## References

-	https://developer.android.com/
-	https://stackoverflow.com/
-	https://www.tutorialspoint.com/index.htm
<<<<<<< HEAD
-	https://medium.com/ 
=======
-	https://medium.com/ 
=======
# clean_me

User Application

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
>>>>>>> 9bca10d (base commit)
>>>>>>> 98b5b7a (base commit)
