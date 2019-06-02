# maven-bom


## maven-jdk8-bom

依赖JDK1.8的第三方jar包

**引入**

```
<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>cn.chenzw.bom</groupId>
            <artifactId>maven-jdk8-bom</artifactId>
            <version>1.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```
