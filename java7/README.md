Java
====

Java based templates for docker using Oracle Linux 6 as base, inspired from the official
docker language template.

These are simple Java Language images using Oracle Linux 6 as a base.  
These all install the JDK and JRE.

The latest build is configured for Java 7

## Quickstart

    $ docker pull dbehnke/java:latest
    
    $ docker run -it dbehnke/java:latest java -version
    java version "1.7.0_71"
    OpenJDK Runtime Environment (rhel-2.5.3.1.0.1.el6-x86_64 u71-b14)
    OpenJDK 64-Bit Server VM (build 24.65-b04, mixed mode)


## Java 6

    $ docker run -it dbehnke/java:6 java -version
    java version "1.6.0_33"
    OpenJDK Runtime Environment (IcedTea6 1.13.5) (rhel-1.13.5.0.el6_6-x86_64)
OpenJDK 64-Bit Server VM (build 23.25-b01, mixed mode)

## Java 7

    $ docker run -it dbehnke/java:7 java -version
    java version "1.7.0_71"
    OpenJDK Runtime Environment (rhel-2.5.3.1.0.1.el6-x86_64 u71-b14)
    OpenJDK 64-Bit Server VM (build 24.65-b04, mixed mode)

## Java 8

    $ docker run -it dbehnke/java:8 java -version
    openjdk version "1.8.0_25"
    OpenJDK Runtime Environment (build 1.8.0_25-b17)
    OpenJDK 64-Bit Server VM (build 25.20-b23, mixed mode)
