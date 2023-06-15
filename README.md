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

#### Spring Cloud Alibaba关联各组件版本

| Spring Cloud Alibaba Version                     | Sentinel Version | Nacos Version | RocketMQ Version | Dubbo Version | Seata Version    |
|--------------------------------------------------|------------------|---------------|------------------|---------------|------------------|
| 2022.0.0.0-RC2                                   | 1.8.6            | 2.2.1         | 4.9.4            | ~             | 1.7.0-native-rc2 |
| 2021.0.5.0                                       | 1.8.6            | 2.2.0         | 4.9.4            | ~             | 1.6.1            |
| 2.2.10-RC1                                       | 1.8.6            | 2.2.0         | 4.9.4            | ~             | 1.6.1            |
| 2022.0.0.0-RC1                                   | 1.8.6            | 2.2.1-RC      | 4.9.4            | ~             | 1.6.1            |
| 2.2.9.RELEASE                                    | 1.8.5            | 2.1.0         | 4.9.4            | ~             | 1.5.2            |
| 2021.0.4.0                                       | 1.8.5            | 2.0.4         | 4.9.4            | ~             | 1.5.2            |
| 2.2.8.RELEASE                                    | 1.8.4            | 2.1.0         | 4.9.3            | ~             | 1.5.1            |
| 2021.0.1.0                                       | 1.8.3            | 1.4.2         | 4.9.2            | 2.7.15        | 1.4.2            |
| 2.2.7.RELEASE                                    | 1.8.1            | 2.0.3         | 4.6.1            | 2.7.13        | 1.3.0            |
| 2.2.6.RELEASE                                    | 1.8.1            | 1.4.2         | 4.4.0            | 2.7.8         | 1.3.0            |
| 2021.1、2.2.5.RELEASE、2.1.4.RELEASE、2.0.4.RELEASE | 1.8.0            | 1.4.1         | 4.4.0            | 2.7.8         | 1.3.0            |
| 2.2.3.RELEASE、2.1.3.RELEASE、2.0.3.RELEASE        | 1.8.0            | 1.3.3         | 4.4.0            | 2.7.8         | 1.3.0            |
| 2.2.1.RELEASE、2.1.2.RELEASE、2.0.2.RELEASE        | 1.7.1            | 1.2.1         | 4.4.0            | 2.7.6         | 1.2.0            |
| 2.2.0.RELEASE                                    | 1.7.1            | 1.1.4         | 4.4.0            | 2.7.4.1       | 1.0.0            |
| 2.1.1.RELEASE、2.0.1.RELEASE、1.5.1.RELEASE        | 1.7.0            | 1.1.4         | 4.4.0            | 2.7.3         | 0.9.0            |
| 2.1.0.RELEASE、2.0.0.RELEASE、1.5.0.RELEASE        | 1.6.3            | 1.1.1         | 4.4.0            | 2.7.3         | 0.7.1            |

#### Spring Cloud Alibaba <-> Spring Cloud <-> Spring Boot版本

| Spring Cloud Alibaba Version | Spring Cloud Version        | Spring Boot Version |
|-----------------------------|-----------------------------|---------------------|
| 2021.0.5.0                  | Spring Cloud 2021.0.5       | 2.6.13              |
| 2021.0.4.0                  | Spring Cloud 2021.0.4       | 2.6.11              |
| 2021.0.1.0                  | Spring Cloud 2021.0.1       | 2.6.3               |
| 2.2.7.RELEASE               | Spring Cloud Hoxton.SR12    | 2.3.12.RELEASE      |
| 2021.1                      | Spring Cloud 2020.0.1       | 2.4.2               |
| 2.2.6.RELEASE               | Spring Cloud Hoxton.SR9     | 2.3.2.RELEASE       |
| 2.1.4.RELEASE               | Spring Cloud Greenwich.SR6  | 2.1.13.RELEASE      |
| 2.2.1.RELEASE               | Spring Cloud Hoxton.SR3     | 2.2.5.RELEASE       |
| 2.2.0.RELEASE               | Spring Cloud Hoxton.RELEASE | 2.2.X.RELEASE       |
| 2.1.2.RELEASE               | Spring Cloud Greenwich      | 2.1.X.RELEASE       |
| 2.0.4.RELEASE(停止维护，建议升级)    | Spring Cloud Finchley       | 2.0.X.RELEASE       |
| 1.5.1.RELEASE(停止维护，建议升级)    | Spring Cloud Edgware        | 1.5.X.RELEASE       |


#### 2.2.x 分支
| Spring Cloud Alibaba Version | Spring Cloud Version        | Spring Boot Version |
|------------------------------|-----------------------------|---------------------|
| 2.2.10-RC1\*                 | Spring Cloud Hoxton.SR12    | 2.3.12.RELEASE      |
| 2.2.9.RELEASE                | Spring Cloud Hoxton.SR12    | 2.3.12.RELEASE      |
| 2.2.8.RELEASE                | Spring Cloud Hoxton.SR12    | 2.3.12.RELEASE      |
| 2.2.7.RELEASE                | Spring Cloud Hoxton.SR12    | 2.3.12.RELEASE      |
| 2.2.6.RELEASE                | Spring Cloud Hoxton.SR9     | 2.3.2.RELEASE       |
| 2.2.1.RELEASE                | Spring Cloud Hoxton.SR3     | 2.2.5.RELEASE       |
| 2.2.0.RELEASE                | Spring Cloud Hoxton.RELEASE | 2.2.X.RELEASE       |
| 2.1.4.RELEASE                | Spring Cloud Greenwich.SR6  | 2.1.13.RELEASE      |
| 2.1.2.RELEASE                | Spring Cloud Greenwich      | 2.1.X.RELEASE       |
| 2.0.4.RELEASE(停止维护，建议升级)     | Spring Cloud Finchley       | 2.0.X.RELEASE       |
| 1.5.1.RELEASE(停止维护，建议升级)     | Spring Cloud Edgware        | 1.5.X.RELEASE       |


#### 版本参考
- [alibaba github wiki](https://github.com/alibaba/spring-cloud-alibaba/wiki/%E7%89%88%E6%9C%AC%E8%AF%B4%E6%98%8E)
