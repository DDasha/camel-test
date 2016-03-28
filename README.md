# Spring Example

### Introduction
This example shows how to work with files and JMS, using Spring to boot up
Camel and configure the routes.

The example consumes messages from a queue and writes them to the file
system.


### Build
You will need to compile this example first:

	mvn compile

### Run
To run the example type

	mvn camel:run

You can see the routing rules by looking at the java code in the
`src/main/java directory` and the Spring XML configuration lives in
`src/main/resources/META-INF/spring`

To stop the example hit <kbd>ctrl</kbd>+<kbd>c</kbd>

### Documentation

This example is documented at <http://camel.apache.org/spring-example.html>


