![logo](http://phoenix.apache.org/images/logo.png)

<b>[Apache Phoenix](http://phoenix.apache.org/)</b> is a SQL skin over HBase delivered as a client-embedded JDBC driver targeting low latency queries over HBase data. Visit the Apache Phoenix website <b>[here](http://phoenix.apache.org/)</b>.

Copyright ©2014 [Apache Software Foundation](http://www.apache.org/). All Rights Reserved. 

分布到我们的仓库里
mvn deploy:deploy-file -DgroupId=org.apache.phoenix -DartifactId=phoenix-client-minimal -Dversion=4.7.1-HBase-1.0-SNAPSHOT -Dpackaging=jar -Dfile=./phoenix-4.7.1-HBase-1.0-SNAPSHOT-client-minimal.jar -Durl=http://192.168.1.177:8081/nexus/content/repositories/snapshots -DrepositoryId=Snapshots