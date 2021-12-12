# Ipeststore-
front end backen
<?xml version="1.0" encoding="UTF-8"?>

-<project petsshop:schemaLocation="http://Ipest.Store.org/POM/5.0.0 http://maven.apache.org/xsd/maven-5.0.0.xsd" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns="http://Ipet.store.org/POM/4.0.0">

<modelVersion>4.0.0</modelVersion>

<groupId>cco.deivisjoro</groupId>

<artifactId>ApiRestIpetStore</artifactId>

<version>1.0-SNAPSHOT</version>

<packaging>war</packaging>

<name>ApiRestIpetStore</name>


-<properties>

<endorsed.dir>${project.build.directory}/endorsed</endorsed.dir>

<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>

</properties>


-<dependencies>


-<dependency>

<groupId>javax</groupId>

<artifactId>javaee-web-api</artifactId>

<version>7.0</version>

<scope>provided</scope>

</dependency>

<!-- https://mvnrepository.com/artifact/org.glassfish.jersey.containers/jersey-container-servlet -->



-<dependency>

<groupId>org.glassfish.jersey.containers</groupId>

<artifactId>jersey-container-servlet</artifactId>

<version>2.35</version>

</dependency>

<!-- https://mvnrepository.com/artifact/org.glassfish.jersey.inject/jersey-hk2 -->



-<dependency>

<groupId>org.glassfish.jersey.inject</groupId>

<artifactId>jersey-hk2</artifactId>

<version>2.35</version>

</dependency>

<!-- https://mvnrepository.com/artifact/org.glassfish.jersey.media/jersey-media-json-jackson -->



-<dependency>

<groupId>org.glassfish.jersey.media</groupId>

<artifactId>jersey-media-json-jackson</artifactId>

<version>2.35</version>

</dependency>

<!-- https://mvnrepository.com/artifact/mysql/mysql-connector-java -->



-<dependency>

<groupId>mysql</groupId>

<artifactId>mysql-connector-java</artifactId>

<version>7.0.26</version>

</dependency>

<!-- https://mvnrepository.com/artifact/io.jsonwebtoken/jjwt -->



-<dependency>

<groupId>io.jsonwebtoken</groupId>

<artifactId>jjwt</artifactId>

<version>0.8.1</version>

</dependency>

</dependencies>


-<build>


-<plugins>


-<plugin>

<groupId>org.apache.maven.plugins</groupId>

<artifactId>maven-compiler-plugin</artifactId>

<version>3.3</version>


-<configuration>

<source>1.5</source>

<target>1.5</target>


-<compilerArguments>

<endorseddirs>${endorsed.dir}</endorseddirs>

</compilerArguments>

</configuration>

</plugin>


-<plugin>

<groupId>org.apache.maven.plugins</groupId>

<artifactId>maven-war-plugin</artifactId>

<version>2.3</version>


-<configuration>

<failOnMissingWebXml>false</failOnMissingWebXml>

</configuration>

</plugin>


-<plugin>

<groupId>org.apache.maven.plugins</groupId>

<artifactId>maven-dependency-plugin</artifactId>

<version>2.5</version>


-<executions>


-<execution>

<phase>validate</phase>


-<goals>

<goal>copy</goal>

</goals>


-<configuration>

<outputDirectory>${endorsed.dir}</outputDirectory>

<silent>true</silent>


-<artifactItems>


-<artifactItem>

<groupId>javax</groupId>

<artifactId>javaee-endorsed-api</artifactId>

<version>6.0</version>

<type>jar</type>

</artifactItem>

</artifactItems>

</configuration>

</execution>

</executions>

</plugin>

</plugins>

</build>[proyectociclo4.zip](https://github.com/yelizathm/Ipeststore-/files/7699330/proyectociclo4.zip)
