## Download Jenkins [Downloads](https://www.jenkins.io/download/)
###### Download Java Generic package (.war)

## Go to jenkins.war file path and run the command 
###### java -jar jenkins.war


## Run Jenkins in browser
###### http://localhost:8080/

# Steps in Jenkins

1.Enter item name

2.Choose Free style and click ok.

3.In General tab choose GitHub project and give github project link.
###### https://github.com/rajeev66053/docker-jenkins-integration

4. In Source Code Management, choose git and give repository url.
###### https://github.com/rajeev66053/docker-jenkins-integration.git

5. In build Triggers, checked Poll SCM and give your cron job scheduler 
###### * * * * * 

6. In builds, choose Invoke top level maven targets and Goals as install

7. Then go to project and click build Now. In the build history we can see our build.

8 Go to jenkins and  Go tom Manage Jenkins then go to manage plugins add  plugin
###### * CloudBees Docker Build and Publish
###### * Docker
###### * docker-build-step

9. Go to project in jenkins and go to configure then check on build dropdown whether there is Build/Publish docker image  sn docker build and publish option.