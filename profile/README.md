<h1 align="center">confkeeper<h1>

## 介绍

当前组织为配置文件中心(confkeeper)的组织

## 背景介绍

这个项目成立之初的是因为作者公司用的[nacos](https://github.com/alibaba/nacos)作为配置文件中心，该方案有一些痛点:

- 太重，我们只需要用到配置文件的功能，加上jvm占用，直接奔2G去了

- 使用上有些不舒服的地方，又有bug

- docker的mysql镜像使用自定义化构建的，不能很好的备份

~~- 作者自己想学习`golang`尝试~~

...
