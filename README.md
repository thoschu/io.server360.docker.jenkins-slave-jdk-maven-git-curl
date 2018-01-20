# de.server360.docker.jenkins-slave-jdk-maven-git-curl
Docker jenkins slave based on evarga/jenkins-slave with oracle jdk8, maven 3, git and curl preinstalled.

[![](https://images.microbadger.com/badges/image/thoschu/jenkins-slave-jdk-maven-git-curl.svg)](https://microbadger.com/images/thoschu/jenkins-slave-jdk-maven-git-curl "Get your own image badge on microbadger.com")

Jenkins slave based on evarga/jenkins-slave image with:

- oracle jdk 1.8.0_101
- maven 3.3.9
- git 1.9.1 
- curl 7.35.0

Note: sylinks /opt/jdk/latest and /usr/local/apache-maven exist and point to respective folders.

https://hub.docker.com/r/thoschu/jenkins-slave-jdk-maven-git-curl/