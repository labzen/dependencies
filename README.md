![LOGO](http://r7jiu5wkl.hd-bkt.clouddn.com/images/2022/02/19/16-34-57-167.png)

# Labzen Dependencies

![Labzen Dependencies](https://img.shields.io/badge/Labzen-Dependencies-green)
![Maven Central](https://img.shields.io/maven-central/v/cn.labzen/dependencies)
![GitHub](https://img.shields.io/github/license/labzen/dependencies)

![CircleCI](https://img.shields.io/circleci/build/github/labzen/dependencies?token=8953c094c11cf9c1d5ac53befed4eb49b770f4f0)

![GitHub last commit](https://img.shields.io/github/last-commit/labzen/dependencies)
![GitHub commit activity](https://img.shields.io/github/commit-activity/m/labzen/dependencies)

Labzen Dependencies 为所有项目提供依赖版本定义

## Installation

Install with Maven

```xml
  <dependencyManagement>
    <dependencies>
      <dependency>
        <groupId>cn.labzen</groupId>
        <artifactId>dependencies</artifactId>
        <version>{{the latest version}}</version>
        <type>pom</type>
        <scope>import</scope>
      </dependency>
    </dependencies>
  </dependencyManagement>
```
## Documentation

依赖管理会在`cn.labzen:parent`中被引入，除非不选择基于`cn.labzen:parent`作父Maven POM来创建项目，否则不需要理会`Installation`