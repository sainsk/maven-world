Maven notes:
  http://maven.apache.org/download.cgi --> download the binary zip
  export M2_HOME=/home/aartha/java/apache-maven-3.5.0
  export PATH=/home/aartha/java/apache-maven-3.5.0/bin:${PATH}
  aartha@dragonbooster:~/java/apache-maven-3.5.0$ mvn --version
    Apache Maven 3.5.0 (ff8f5e7444045639af65f6095c62210b5713f426; 2017-04-04T01:09:06+05:30)
    Maven home: /home/aartha/java/apache-maven-3.5.0
    Java version: 1.8.0_131, vendor: Oracle Corporation
    Java home: /usr/lib/jvm/java-8-openjdk-amd64/jre
    Default locale: en_IN, platform encoding: UTF-8
    OS name: "linux", version: "4.4.0-87-generic", arch: "amd64", family: "unix"
    aartha@dragonbooster:~/java/apache-maven-3.5.0$
groupId would be same as package-> com.arcspace.mavenworld
mvn compile
mvn package --> generates jar in target folder
to run the class -> java -cp target/MavenTestApp-1.0-SNAPSHOT.jar com.arcspace.mavenworld.App
