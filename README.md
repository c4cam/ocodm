## Compiling, installing and using with Java 8

This is a fork of the https://github.com/OpenClinica/ocodm repository which provides the `openclinica-odm-2.2.jar` file.

This file is referred to by the OpenClinica `pom.xml` file in 

```xml
<dependency>
  <groupId>org.akaza.openclinica.odm</groupId>
  <artifactId>openclinica-odm</artifactId>
  <version>2.2</version>
</dependency>
```

Source: https://github.com/OpenClinica/OpenClinica/blob/3.12/pom.xml#L96-L100

### Changes

This backports the changes made to make [openclinica-odm-2.3.jar](https://github.com/OpenClinica/ocodm/tree/2.3) compilable with Java 8.

The jar file generated remains compatible with Java 6.

### Using

Compiling and packaging:

``` bash
mvn package
```

Installing

``` bash
mvn install
```

