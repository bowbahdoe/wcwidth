# wcwidth

This is a port of the C [wcwidth](https://man7.org/linux/man-pages/man3/wcwidth.3.html) function in pure
Java. The code is taken from JLine.

While I am publishing this as a library, you might also consider just shading the utility into your own project.

You can find examples of similar utilities in other libraries
- [Example 1](https://docs.oracle.com/en/graalvm/jdk/21/sdk/org/graalvm/shadowed/org/jline/utils/WCWidth.html)
- [Example 2](https://github.com/termd/termd/blob/master/src/main/java/io/termd/core/util/Wcwidth.java)

## Dependency Information

### Maven
```xml
<dependency>
    <groupId>dev.mccue</groupId>
    <artifactId>wcwidth</artifactId>
    <version>2024.05.12</version>
</dependency>
```