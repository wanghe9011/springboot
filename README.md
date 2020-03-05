# 简介

Spring Boot示例集合.

# 各模块介绍

## docker-maven-plugin

```shell
git clone git@github.com:wanghe9011/springboot.git
cd springboot
cd maven-docker-plugin
mvn clean package docker:build #打包docker镜像
```

## dockerfile-maven

```shell
git clone git@github.com:wanghe9011/springboot.git
cd springboot
cd maven-dockerfile
mvn clean package
mvn dockerfile:build #打包docker镜像
```

