For code integration examples view:\
    - https://github.com/ModularSoftAU/zander

Instructions:
```shell
# compile library
mvn clean package
```

```shell
# specify as dependency
pom.xml +
...
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>
...
<dependency>
    <groupId>com.github.ModularSoftAU</groupId>
    <artifactId>StoneLib</artifactId>
    <version>1.0</version>
    <scope>provided</scope>
</dependency>
...
```
