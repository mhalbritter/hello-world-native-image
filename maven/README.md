# Native Image Hello World with Maven

## Prerequisites

You'll need a GraalVM installation.

If you're using SDKman, you can install one with

```
sdk install java 22.3.r17-grl
```

or

```
sdk install java 22.3.r17-nik
```

## Building

```
mvn clean package
```

## Running

```
target/hello-world-native-image
```

It should print

```
Hello world from native image built with Maven!
```
