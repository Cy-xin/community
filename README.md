## 社区

## 资料
[spring web文档](https://spring.io/guides/gs/serving-web-content/)

[github oauth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

[SpringBoot-Mybatis](http://www.mybatis.org/spring-boot-starter/mybatis-spring-boot-autoconfigure/)


## 脚本
```sql
CREATE TABLE `user` (
  `id` int(11) NOT NULL AUTO_INCREMENT,
  `account_id` varchar(100) DEFAULT NULL,
  `name` varchar(50) DEFAULT NULL,
  `token` char(50) DEFAULT NULL,
  `gmt_create` bigint(20) DEFAULT NULL,
  `gmt_modified` bigint(20) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=8 DEFAULT CHARSET=utf8;
```
