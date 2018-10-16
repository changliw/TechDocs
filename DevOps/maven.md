## Maven Small Skills ##
#### How can I download libraries with mvn command line? ####
Use the maven-dependency-plugin with 2.1 or higher version. For example:
```bash
mvn org.apache.maven.plugins:maven-dependency-plugin:2.1:get     -DrepoUrl=http://mvnrepository.com/     -Dartifact=org.slf4j:slf4j-log4j12:1.7.10
```