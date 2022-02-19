![LOGO](http://r7jiu5wkl.hd-bkt.clouddn.com/images/2022/02/19/16-34-57-167.png)

# Labzen Dependencies

![Labzen Dependencies](https://img.shields.io/badge/Labzen-Dependencies-green)

![GitHub](https://img.shields.io/github/license/labzen/labzen-dependencies)

Labzen Dependencies 为所有项目提供依赖版本定义

## Installation

Install with Maven

```xml
  <dependencyManagement>
    <dependencies>
      <dependency>
        <groupId>org.labzen</groupId>
        <artifactId>dependencies</artifactId>
        <version>{{the latest version}}</version>
        <type>pom</type>
        <scope>import</scope>
      </dependency>
    </dependencies>
  </dependencyManagement>
```
## Documentation

依赖管理会在`org.labzen:parent`中被引入，除非不选择基于`org.labzen:parent`作父Maven POM来创建项目，否则不需要理会`Installation`