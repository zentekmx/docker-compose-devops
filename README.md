# docker-compose-devops
Docker compose for devops tools:
* gitlab at https://about.gitlab.com/
* sonarqube at https://www.sonarqube.org/
* nexus at https://www.sonatype.com/products/repository-oss
* jenkins at https://www.jenkins.io/

Fix permissins with:
chown -R 200:200 ${NEXUS_VOLUME_DATA}
chown -R 1000:1000 ${JENKINS_VOLUME_HOME}

