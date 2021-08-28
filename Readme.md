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
- clone and navigate to https://github.com/udujoel/java_maven_project.git
run:
```bash
mvn clean package
```

- CD to the /target folder to see the .jar package

- for reporting:
```bash
mvn clean package site
```
- CD to /site and open index.html

#### Parent POM (Project Object Model)
POM is the single touchpoint for a project managed by Apache Maven.
Parent POM is used to organise a larger project, and specify authorised artifacts at a parent level. Individual modules hold thier poms defining thier dependencies. 

### LifeCycles
- Default - for main lifecycle
- Clean - cleans the project
- Site - generates project documentation


