
```sh
cd spring-start-sample
mvn io.fabric8:fabric8-maven-plugin:3.4.0:setup
mvn clean install -Dfabric8.mode=openshift
mvn fabric8:deploy -Dfabric8.mode=openshift
```        
