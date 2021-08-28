[![Java CI with Maven](https://github.com/udujoel/java_maven_project/actions/workflows/maven.yml/badge.svg)](https://github.com/udujoel/java_maven_project/actions/workflows/maven.yml)

### Jave Folder structure
![](https://i.imgur.com/9ipF8aY.png)


[maven](https://https://maven.apache.org)

You'll need to have JDK installed
```bash
sudo apt install openjdk-11-jdk
```
- Download and extract mvn
- Set both java (JAVA_HOME) and mvn to path.
- confirm with:
```bash
mvn -v
java -version
```
- navigate to https://github.com/udujoel/java_maven_project.git
run:
```bash
mvn clean package
```
- for reporting:
```bash
mvn clean package site
```