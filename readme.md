# web-java-spring-petclinic

Spring PetClinic Sample Application

# Developer Workspace
[![Contribute](https://codenvy.io/factory/resources/codenvy-contribute.svg)](https://codenvy.io/f?id=factoryzheekelodx3wdwnn
)

# Stack to use

FROM [codenvy/ubuntu_jdk8](https://hub.docker.com/r/codenvy/ubuntu_jdk8/)

or


FROM [codenvy/debian_jdk8](https://hub.docker.com/r/codenvy/debian_jdk8/)

# How to run

| #       | Description           | Command  |
| :------------- |:-------------| :-----|
| 1      | Build and copy war | `mvn -f ${current.project.path} clean install && cp ${current.project.path}/target/*.war $TOMCAT_HOME/webapps/ROOT.war` |
| 2      | Run Tomcat      |   `$TOMCAT_HOME/bin/catalina.sh run` |
| 3 | Stop Tomcat      |    `$TOMCAT_HOME/bin/catalina.sh stop` |
| 4 | Tomcat Debug Mode      |    `$TOMCAT_HOME/bin/catalina.sh jpda run` |

