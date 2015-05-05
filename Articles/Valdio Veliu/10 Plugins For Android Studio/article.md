#Top 8 plug-ins for Android Studio

Android Studio is the official Google IDE designed for native Android application development, based on JetBrains’ IntelliJ IDEA. It was first announced at Google I/O 2013 as the successor to Eclipse and was welcomed by the Android community, albeit with some criticism as is normal in such cases. After a long beta phase, the final version was announced in December of last year. 

On its own Android Studio is a fully-featured development environment equipped with the complete tools needed to develop Android applications for all devices, from smart watches to automobiles.

But there is always space  for improvement, and luckily Android Studio offers support for third party plug-ins,so today i’m going to list some of the most useful ones for your developing needs.

##1. H.A.X.M (Hardware Accelerated Execution Manager)

H.A.X.M is the best way for developers who use the Android Emulator to execute their applications faster. H.A.X.M provides hardware acceleration for Android SDK emulators on Intel systems. It uses Intel Virtualization Technology (Intel VT) build on top of virtualization hardware VT-x, meaning processors that support virtualization, this way giving you the fastest way to run your application on simulated Android environments. 
I think that H.A.X.M is the most useful plugin that an Android developer must have to run the latest Android version on the emulator as fast as it can get.


To install H.A.X.M follow this steps: 

 Open the Android SDK Manager select the “Intel x86 Emulator Accelerator (HAXM installer)” accept the license and  install the package. 
 
![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/haxm.PNG)
 
 This process has downloaded the package but has not actually installed H.A.X.M. To finish the installation go to the SDK path shown in the image above “C:\Users\Administrator\AppData\Local\Android\sdk\” (This installation is done on a Windows machine) and try to find the download folder. Mine was on “C:\Users\Administrator\AppData\Local\Android\sdk\extras\intel”  open the installation  folder “Hardware_Accelerated_Execution_Manager” and click the executable intelhaxm-android and continue the installation. After this installation you are all set to use the emulator. 

![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/haxmexe.PNG)




##2. Genymotion

![](https://raw.githubusercontent.com/valdio/SitePoint-Mobile-Channel/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/0.PNG)


Genymotion is the ultimate tool for testing your Android application and enables you to run custom versions of Android, built for execution inside VirtualBox and equipped with the complete set of sensors and features in order to interact with a virtual Android environment.  With Genymotion, you can test your Android applications on a wide range of virtual devices for development and its emulators are a lot faster than the native Android ones. 

Every developer who wants to make sure his/her application runs smoothly in every supported device and has trouble troubleshooting specific device errors should make use of this great plugin.


To install Genymotion go to the official Genymotion page  www.genymotion.com create an account and then you should be able to download and install you Genymotion based on the Operating System you are working on. 




##3. Android Drawable Importer

![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/drawable1.PNG)

![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/drawable2.PNG)



To adapt to all the Android screen sizes and densities each Android project contains the drawable section. Any developer with a bit of experience on Android development  should know that to support all the screen sizes you must import different types of drawables for each of the screen types. 
Android Drawable Importer makes this job easier. It reduces your efforts to import scaled images into the Android project. Android Drawable Importer adds an option on IntelliJ to import drawables in different resolution or scale a specified image to a defined resolution. 
This plugin is the most useful tool that that every developer must try to speed up his work with the application drawables.

Install Drawable Importer:
![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/Drawable%20Importer.gif)


##4. Android ButterKnife Zelezny

Android ButterKnife is a “View Injection Library for Android”. It gives a better view of the code and makes it more readable. ButterKnife is a great library, which allows you to focus on the logic rather than on the glue code for finding views or adding listeners.
In programing with ButterKnife you have to perform injection on arbitrary objects. Basically  you have to write your injection in this form:

     @InjectView(R.id.title) TextView title;

If you have one or two injection writing them is not a problem, but if you have many injections needed to be made you need to refer to all the layout XMLs to write them on the source file. 

Android ButterKnife Zelezny is a Android Studio Plugin for generating ButterKnife injections from selected layout XMLs in activities, fragments or adapters. This plugin will provide the fastest way to generate your XML object injections. 

Here is an example how the code looks like:
Before using Android ButterKnife
![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio Veliu/10 Plugins For Android Studio/images/bk1.PNG)

After using  Android ButterKnife:

![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/bk2.PNG)


Install ButterKnife Zelezny:
![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/ButterKnife%20Zelezny.gif)

##5.Android Holo Colors Generator

To develop cool Android applications you should have a nice design of the application layout. Android Holo Colors Generator is the best and easiest way to customize your Android application catered to your own preferences. 
Android Holo Colors Generator is a  IntelliJ/Android Studio Plugin that allows you to easily create Android layout components with your own colours for your application. This plugin will generate all the necessary assets associated with XML drawables and styles to use in your project.

Install Holo Colors Generator:
![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/Holo%20Colors%20Generator.gif)


##6. Robotium Recorder
Robotium Recorder is a test automation framework for testing native and hybrid mobile application on emulators and Android devices. With Robotium Recorder it is possible to record test cases and user actions. You can view functions of system and user test scenarios on different Android activities.  
With Robotium Recorder you can actually see what's happening with your application when it runs on your device,  if it is working as it is supposed to or if it reacts properly to user actions.
For everyone who is looking to develop stable Android applications this plugin might be very helpful for testing applications.

 Here is an example of my application recorded on Robotium Recorder:

![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/Robotium.jpg)


To install Robotium Recorder go to the official page robotium.com, in the Installation section and choose your version of Robotium Recorder based on your Operating System. 


##7. jimu Mirror

Android Studio is equipped with a visual layout editor out of the box, but a static preview of the layout might not be enough. 
Is not possible on a static preview to preview animation, colours and touch zones so jimu Mirror is a plugin that allows you to test your layout on the fly on a real device. 
jimu Mirror gives you on-device previews of Android layouts that update as you code.
This plugin offers you a realistic context before writing the java code to link the application together. 

Install jimu Mirror:
![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/jimu%20Mirror.gif)

##8. strings-xml-tools

Strings-xml-tools is a small but very useful plugin that can be used to manage the string resources in Android projects. It provides basic operations of sorting entries in Android localization files and adding missing strings. There are limited things that you can with this plugin but if your application has a large number of of string resources this plugin might be helpful. 

Install Android Strings.xml tools:

![](https://github.com/valdio/SitePoint-Mobile-Channel/blob/master/Articles/Valdio%20Veliu/10%20Plugins%20For%20Android%20Studio/images/Android%20Strings.xml%20tools.gif)




