A-step-further-basics
=====================

There are few main application components .
-Activity
  Every thing is an activity. We develop interface as an activity only.

-Service
  Service is the basic thing that is needed to run any application. It is just like database service and will work accordingly.
  
-BroadcastReceiver
  There are broadcast done which cna be recieved by device by broad cast reciever. Like the updates coming can be recieved by the broadcast reciever.
  It isnot necessary for bradcast recievr to work with service.
  braod cast reciever is filtered by intentclass. 
  _--- Any thing which your system is continously listening is broadcast reciever.
  
-Content provider
  it is used to share data between the application of a device.
  as example. Instagram is showing photos from your phone. So two application is interfacing.

Applications.


Activity...
  IT is the primary thing to be done. It is primary class for user interaction.
  it implements a single focus task.

Service
  -It runs in the background.
  -To perform long running application.
  -To support interaction with remote proces

BroadcastReceiver
  -If it related to hardware than it will give the information to andriod OS and than it will do the broadcast and it is recieved by your service.

ContenProvider
  Store and share data across application.
  
  
Flow to make and application.
- Andriod Project.
- Compiling and packaging. (packaging everything in .apk file.)
- Andriod package(.apk)
  - .dsk files
  - resources
  - uncompiled resources
  - Andriod varilest.xml
- Signing.(It is used to generate a key store for security). It is provided by sdk(ti will be based on develop account)
- Immulation

Define resources
- Resources are non-source code entiites.
many different resources are there. -- layout,string,images,menus & animations

To diffenrentiate different things android provides string resource class, static resource class....
We can get that from getstring.
We are storing the refrence in this case.




------------------------------------------------------
To access any thing in java code than we can access it from r.java.
to access string class variable we are using @ sign with string. - Then we use the command getstring , getdrawable.

========Secontentview=====
it will get the layout referred by r.layout.activity_mname.
it will be attached to the activity of the main.
setContentView is case senisitive



=======Multiple layout============
For Potraiit it is port............for landscape it is land
to add landscape layout create layout_land for layout folder.



Restoring of data is done on oncreate method.
we can initialize the items on onclick .



AndroidManifest.xml
It contains information:
  applicaiton name
  compnents
  other
  ------> Find out all the components in android manifest file and details about them


ADB is the adriod debug bridge
%adb install <path_to_apk>
