mvn clean package deploy -DmuleDeploy -Dpassword=***
mvn mule:undeploy -Dmule.artifact=target/*.jar -DmuleDeploy -Dpassword=***