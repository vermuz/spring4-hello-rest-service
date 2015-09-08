This is a simple Spring 4 REST service to test understanding of Gradle and Spring 4's promising new @RestController.

```java
maniali@mani-mint ~/workshop $ gradle clean
:clean

BUILD SUCCESSFUL

Total time: 5.141 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.8-20150907220034+0000/userguide/gradle_daemon.html
maniali@mani-mint ~/workshop $ gradle build
:compileJava
:processResources UP-TO-DATE
:classes
:jar
:startScripts
:distTar
:distZip
:bootRepackage
:assemble
:compileTestJava UP-TO-DATE
:processTestResources UP-TO-DATE
:testClasses UP-TO-DATE
:test UP-TO-DATE
:check UP-TO-DATE
:build

BUILD SUCCESSFUL

Total time: 7.726 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.8-20150907220034+0000/userguide/gradle_daemon.html

maniali@mani-mint ~/workshop $ java -jar build/libs/restdemo-0.1.0.jar 

  .   ____          _            __ _ _
 /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
 \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
  '  |____| .__|_| |_|_| |_\__, | / / / /
 =========|_|==============|___/=/_/_/_/
 :: Spring Boot ::        (v1.0.2.RELEASE)

2015-09-08 03:43:39.366  INFO 452 --- [           main] com.parimala.demo.Application            : Starting Application on mani-mint with PID 452 (/home/maniali/workshop/build/libs/restdemo-0.1.0.jar started by maniali in /home/maniali/workshop)
```

http://localhost:8080/hello/mani
