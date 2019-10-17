# maven-repo
个人maven仓库

## Usage
pom.xml:
```xml
    <repositories>
        <repository>
            <id>alvin_maven_repo</id>
            <url>https://raw.githubusercontent.com/alvin198761/maven-repo/master/repository</url>
        </repository>
    </repositories>
```
```java
mvn install:install-file -Dfile="D:\test.jar" -DgroupId=org.alvin.test -DartifactId=test -Dversion=3.2.0 -Dpackaging=jar
```