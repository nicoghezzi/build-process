# Demo of Build Process

## Build Process Requisites

Objective: Upload the Java App JAR to a Nexus Repository 

a. Installed and Run Nexus on Digital Ocean (Ubuntu)
b. Opened port 8081 by modifying Networking settings.
c. When you run Nexus, the app creates a default repository.
d. Open the pom.xml and configure Nexus URL
e. Added credentials within .m2 so that Nexus allow me to upload remotely.
f. Once all of these requisites are done, I followed these steps:

Step 1: Build the JAR (mvn package)

![Lighthouse Report](/images/builtmvpackageprocess.png)

Step 1: Deploy JAR to Nexus (mvn deploy)

![Lighthouse Report](/images/mvndeploy.png)

Step 1: Review Artifact in Nexus Repository

![Lighthouse Report](/images/artifactjavamaven.png)


## Build in CircleCI

Step 1: Create a config file

![Lighthouse Report](/images/1createconfigfile.png)

Step 2: Make basic change and commit change

![Lighthouse Report](/images/2commmitchange.png)

Step 3: Open CircleCI with a previously repository in Github

![Lighthouse Report](/images/3opencircleci.png)

Step 4: Review CircleCI Build Process 

![Lighthouse Report](/images/4reviewbuildprocess.png)

Step 5: Refresh Github Repository 

![Lighthouse Report](/images/5refreshgithubrepository.png)

Step 6: Review comment 

![Lighthouse Report](/images/6reviewcomment.png)