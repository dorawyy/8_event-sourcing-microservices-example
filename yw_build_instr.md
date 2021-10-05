The app uses Java 11 and Maven. 
If you are using a Windows machie, ensure your `JAVA_HOME` points to JDK11. 


My build enironment: 
```
> mvn --version
Apache Maven 3.8.2 (ea98e05a04480131370aa0c110b8c54cf726c06f)
Maven home: C:\Program Files\apache-maven-3.8.2
Java version: 11.0.12, vendor: Eclipse Foundation, runtime: C:\Program Files\Eclipse Foundation\jdk-11.0.12.7-hotspot
Default locale: en_CA, platform encoding: Cp1252
OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"
```

```
> java --version

openjdk 11.0.12 2021-07-20
OpenJDK Runtime Environment Temurin-11.0.12+7 (build 11.0.12+7)
OpenJDK 64-Bit Server VM Temurin-11.0.12+7 (build 11.0.12+7, mixed mode)
```

```
> javac --version

javac 11.0.12
PS C:\Users\dora9\yw\springApps\8_event-sourcing-microservices-example> 
```


To generate service jars: 
```
// cd to project root dir 
mvn clean package -DskipTests
```

The app does not use config server.