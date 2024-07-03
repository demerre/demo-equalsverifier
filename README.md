# EqualsVerifier Demo

This project demonstrates how to use EqualsVerifier, a Java library that simplifies testing `equals` and `hashCode` methods.

## What is EqualsVerifier?

EqualsVerifier is a Java library that helps you test the `equals` and `hashCode` methods of your classes. It provides a simple and automated way to ensure that these methods are implemented correctly and adhere to the contracts specified by the Java language.

## Download/Dependency

To include EqualsVerifier in your project, add the following dependency to your `pom.xml`:

```xml
<dependency>
    <groupId>nl.jqno.equalsverifier</groupId>
    <artifactId>equalsverifier</artifactId>
    <version>3.15.4</version>
    <scope>test</scope>
</dependency>
