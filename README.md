# thriveapp-appium
Appium Automation of the Thrive App

## Getting Started
Use these instructions to configure your local environment to run Appium Automated test scripts. Please note that these instructions are for writing Appium scripts in Java with Eclipse as the IDE
### Prerequisites
1. Install Xcode(ex: Vesrion 10.1)
2. Install Android Studio (ex: Version 3.2.1)
3. Install a Java IDE (ex: Eclipse Version 4.10)
4. Checkout the thriveapp-appium git repository on your local machine

### Steps to Configure External JARS
``` NOTE: External JARS are very picky about who they play with. Version numbers are key during this process, so if you run into issues make sure that all of your version numbers are compatible. The version numbers used for my initial setup are included as examples in each line item as a reference```

``` RESOURCE: Appium JARSs to download: http://www.automationtestinghub.com/appium-jars-download/ ```
1. Open the thriveapp-appium repository in Eclipse and right click on the project name. Select Properties > Java Build Path > Add External JARS
2. Import the following JARS>
5. Download the following files and add them to the Project Build Path in Eclipse:
  * [Appium JAR](https://mvnrepository.com/artifact/io.appium/java-client/6.1.0) - Java Client JAR file (ex: version 6.1.0)
  * [Selenium Jars]( https://www.seleniumhq.org/download/) - For Java (ex: version 3.141.59) 
  ```NOTE: Download all the JAR files in the main selenium downloaded folder, and in the "libs" sub-directory folder ```
  * [JUNit JAR](https://mvnrepository.com/artifact/junit/junit/4.12) - (ex: version 4.12)
  * [commons-langs](https://mvnrepository.com/artifact/org.apache.commons/commons-lang3/3.8.1) - (ex: version 3.8.1)
  * [hamcrest-core](https://mvnrepository.com/artifact/org.hamcrest/hamcrest-core/2.1) - (ex: version 2.1)
  * [HTTPCore Jar](https://mvnrepository.com/artifact/org.apache.httpcomponents/httpcore/4.4.4) - (ex: version 4.4.4)

## Tips for Setting Up Desired Capabilities
1. A file method is used to map to the .apk file. To properly use this method, please place the target apk file(s) in the source folder and change the name of the file in the file method.
