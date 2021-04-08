# Jenkins Sandbox
A sanbox project for exploring the Jenkins Automation Server.


## Prerequisites for Exploring Jenkins
I am running Jenkins based on the "Regular Releases" by using the Generic Java Package (.war) from the [Jenkins Downloads page](https://www.jenkins.io/download/).

To run this on my macOS development machine, I will also need to [install Java's AdoptOpenJDK](https://adoptopenjdk.net/installation.html).

## Running Jenkins
We can run Jenkins from the macOS Terminal by executing the following command, granted the prerequisites have been satisfied.

```
java -jar jenkins.war
```

After Jenkins has started it should inform you of the installation password as follows:

```
*************************************************************
*************************************************************
*************************************************************

Jenkins initial setup is required. An admin user has been created and a password generated.
Please use the following password to proceed to installation:

abcdef0123456789abcdef0123456789

This may also be found at: /Users/username/.jenkins/secrets/initialAdminPassword

*************************************************************
*************************************************************
*************************************************************

```
