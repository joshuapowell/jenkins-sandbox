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
*************************************************************<img width="1648" alt="Screen Shot 2021-04-08 at 2 42 17 PM" src="https://user-images.githubusercontent.com/569351/114079805-9f3cee00-9878-11eb-8f5d-7696f8f9c468.png">


Jenkins initial setup is required. An admin user has been created and a password generated.
Please use the following password to proceed to installation:

abcdef0123456789abcdef0123456789

This may also be found at: /Users/username/.jenkins/secrets/initialAdminPassword

*************************************************************
*************************************************************
*************************************************************

```

## Launch Jenkins
Open a browser and navigate to [http://localhost:8080](http://localhost:8080)

### Plugins
For the purposes of this guide, we will not install any custom plugins yet. However, I will make note of the [Jenkins Plugins Index](https://plugins.jenkins.io) that is available to us. We will want to revisit this once we have progressed in our knowledge of Jenkins.

## Installing Jenkins

### Unlock Jenkins
<img width="1648" alt="Screen Shot 2021-04-08 at 2 43 00 PM" src="https://user-images.githubusercontent.com/569351/114079919-bda2e980-9878-11eb-963c-0fa40ae2fc06.png">

### Customize Jenkins
Select "Install suggested plugins".

<img width="1648" alt="Screen Shot 2021-04-08 at 2 43 24 PM" src="https://user-images.githubusercontent.com/569351/114080015-ddd2a880-9878-11eb-8eab-76b3476ff433.png">
