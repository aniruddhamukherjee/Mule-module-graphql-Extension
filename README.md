# Mule-module-graphql-Extension

This project will build a custom plugin which can be added to any Mule 4 app to implement GraphQL capabilities.

# Prerequisites

jdk 8+
maven 3.x

# Build 
mvn clean install

This command will build a jar which can then be added as a maven dependency like below:
<dependency>
			<groupId>com.mulesoft.services</groupId>
			<artifactId>mule-module-graphql</artifactId>
			<version>1.0.0-SNAPSHOT</version>
			<classifier>mule-plugin</classifier>
</dependency>
