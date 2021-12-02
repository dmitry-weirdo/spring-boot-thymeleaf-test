# Relate links

* https://github.com/thymeleaf/thymeleaf-spring/issues/263
* https://github.com/spring-projects/spring-boot/issues/28893


# Build
```shell
mvn clean
mvn install
```

# Export maven dependencies to file
```shell
mvn dependency:tree -DoutputFile=c:/java/ins-new/mvn-deps.txt
```

# Execute dependency check maven plugin
```shell
mvn package dependency-check:check -Dmaven.test.skip=true
```
