# WHAT ARE BUILD AND PACKAGE MANAGER TOOLS

- App need to be deployed on a production server
- Package application into a single movable file
- Application code and its dependencis
when u have build the code in a buld folder it call application artifact
packaging = building the code

## Building the co de : compiling, compress, hundreds to 1 single file

    Keep artifact in storage
    to deploy it multiple time, have backup etc.
were artifact are kept are Artifact respository
were there kept : Nexus, JFrog Artifactory

What kind of file is the artifact
Artifact file looks diffent for each programming language
for Java = JAr OR WAR file, Jar = java Archive
maven use xml
Gradle use Groovy and it more confinent to rewrite automated script

run it on server
java -jar filename

javascript build file : npm and yarn : for tag npm pack
when having frontend and backend for java code we package in war file
pip for pyton

push or publish to artifact reporiistory but we can push manually because docker and jerkings
for Docker this elimate multiple repository for artifact and we can now use i docker image for deployment
your woud still have use webpack for js to compress and jar file for java for compress to make it lighter in docker

Build Tools For Devops Engineers

Why should you know these build tools

- Help Developers for building the application
- Because you Know where and how it will run -> Developers install deps locally and run the app, but don't build it locally
Build Docker Image ==> push to Repo ==> Run on Server all happen in a devops engineer mechine because of the automation tools
you need to configure the build automation to CI?CD Pipeline
install dependencies    run tests   build/bundle app    push to repo
never you run the app localally without docker

docker
    you need to excute tests on the build servers
    Build and package into Image
