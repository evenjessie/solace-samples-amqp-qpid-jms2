
## Obtaining Apache Qpid JMS 2.0 API

This tutorial assumes you have downloaded and successfully installed the [Apache Qpid JMS client](https://qpid.apache.org/components/jms/index.html). If your environment differs from the example, then adjust the build instructions appropriately.

The easiest way to install it is through Gradle or Maven.

### Get the API: Using Gradle

```
dependencies {
    compile("org.apache.qpid:qpid-jms-client:0.23.+")
}
```

### Get the API: Using Maven

```
<dependency>
    <groupId>org.apache.qpid</groupId>
    <artifactId>qpid-jms-client</artifactId>
    <version>[0.23,)</version>
</dependency>
```
