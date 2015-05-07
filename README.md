#Traxia Repositories

These are the libraries we use for our production environment.  Compiled to work with Java 7 and above.


##The Libraries

 * [**aws-tomcat-deploy**](https://github.com/aaronfreeman/aws-tomcat-deploy) - Gradle plugin to deploy to Tomcat, made specifically to work with the AWS infrastructure.

##Usage
To use any of these libaries with Gradle, include the following in your `build.gradle` file

    buildscript {
        repositories {
            ivy { url "https://raw.github.com/adelo/repo/master" }
        }

        dependencies {
            classpath 'traxia:aws-tomcat-deploy:1.1.2'
        }
    }
