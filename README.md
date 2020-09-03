# Instructions d'installation

## Description :
This library is developed to bring together the common functionalities used by the projects in production.

## Requirements :
To be able to use this library you need at leasted **java 5** in your project.

## Releases :
This is the first version.

## Building :
To build this library you need `maven 3`. To build it use : 
```sh
mvn clean install
```

## Using the library :
To use the library in your project, you have chooses : 
**With a jar file :**
For that you need to build the library (previous step) and add the jar file in your project dependencies.
**With maven :**
If your project was developped with maven, you can found the library in the local repository of the company. You just need to add the dependency in your `pom.xml` like that :
```xml
<dependency>
	<groupId>com.adneom</groupId>
	<artifactId>commons</artifactId>
	<version>0.0.1-SNAPSHOT</version>
</dependency>
```
