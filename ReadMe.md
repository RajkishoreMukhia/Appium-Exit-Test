# Testing ApiDemos-debug Application

Testing features of ApiDemos-debug.apk mobile application using Appium. 

## Description

It is a BDD based framework using Cucumber. For testing mobile application using Appium, Java, TestNg, Cucumber etc.

We are written some test cases for testing some of the features of the application.
All the test cases are written in Feature File and its crossponding Step Defination. Then we run the the code through TestRunner and Maven.

Here is some exmaple of Feature File test cases

	1 .Animation->Hide-Show Animations 
		TestCase1 – Verify Hiding of buttons
		TestCase2 – Verify Showing of buttons
	2. App-> Action Bar-> Display Options 
		TestCase3 – Verify Display_Show_title option click


### Dependencies
We are using maven dependencies in our [pom.xml](https://github.com/RajkishoreMukhia/AppiumTest/blob/1c275442e8ed072fd966adc9fd9d6d3cc4083c41/pom.xml) file. Please refer this link for all the POM dependencies are needed. 

### Built With 

* [Appium](https://github.com/appium/appium-desktop/releases/tag/v1.18.0-1)
* [TestNG](https://mvnrepository.com/artifact/org.testng/testng)
* [Maven](https://maven.apache.org/download.cgi )
* [Java](https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html )
* [Cucumber](https://cucumber.io/docs/installation/java/)

### Roadmap


### Executing program

* To run the program 

```
Click src/test/java --> TestRunner --> Runner.java
```

* To run single feature file 

```
Use tags = @tags name 
e.g @ani, @dis or @rev
```

* To run all Feature file at onces

```
Use tag = @smoke
```
* To run from Command prompt

```
Open BatchFile --> click on Run.bat 
```
* Also to run from Command prompt

```
Right click on project file --> Show In --> Terminal 
```
```
Then enter this code : mvn test -Dcucumber.options="--tags @tag Name" 
```
```
tag Name = @ani, @dis, @rev, @smoke
```

## Contact

Rajkishore Mukhia - [@GitUb](https://github.com/RajkishoreMukhia) - [@Gmail](rajkishoremukhia@gmial.com)

Project Link: [https://github.com/RajkishoreMukhia/Appium-Exit-Test.git](https://github.com/RajkishoreMukhia/Appium-Exit-Test.git)

## Application

[ApiDemos-debug.apk](https://github.com/RajkishoreMukhia/Appium-Exit-Test/blob/7238ebc38ec8a428a449658721d686629e4ebe2e/Application/ApiDemos-debug.apk)

## Acknowledgments

[Youtube](https://www.youtube.com/c/pavanoltraining)

[Stackoverfow](https://stackoverflow.com/)

[Toolsqa](https://www.toolsqa.com/extent-report/extent-report-for-cucumber-testng-project/)