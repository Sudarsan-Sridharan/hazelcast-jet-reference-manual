# Getting Started

## Requirements

Jet requires a minimum JDK version of 8.

The easiest way to start using Jet is to add it as a dependency to your
project.

## Maven

```xml
<dependencies>
 <dependency>
  <groupId>com.hazelcast.jet</groupId>
  <artifactId>hazelcast-jet</artifactId>
  <version>0.3</version>
 </dependency>
</dependencies>
```

## Gradle

```groovy
compile 'com.hazelcast.jet:hazelcast-jet:0.3'
```

## Download

Alternatively, you can download the latest [distribution package for Jet](http://jet.hazelcast.org/download/)
and add the `hazelcast-jet-<version>.jar` file to your classpath.

### Distribution package

The distribution package contains some scripts to help you get started
with Jet:

* `bin/start.sh` and `bin/start.bat` start a new Jet member in the
current directory.
* `bin/stop.sh` and `bin/stop.bat` stop the member started in the
current directory.
* `bin/cluster.sh` provides basic functionality for Hazelcast cluster
manager, such as changing cluster state, shutting down the cluster or
forcing the cluster to clean its persisted data.

Note: `start.sh` / `start.bat` scripts lets you start one Jet member per
folder. To start a new instance, please unzip the package in a new folder.
