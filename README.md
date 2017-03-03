# Spring-Boot-Templates
Spring Boot In Action
## Project Starter
使用**[Spring Starter](http://start.spring.io/)**创建Maven项目，导入到Eclipse中
- 添加Web依赖
```xml
<dependency>
  <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-starter-web</artifactId>
</dependency>
```
- 添加DevTools,开发模式下可热启动
```xml
<dependency>
  <!-- 开发模式下热启动配置 -->
      <groupId>org.springframework.boot</groupId>
      <artifactId>spring-boot-devtools</artifactId>
      <optional>true</optional>
</dependency>
```
- 使用@RestController注解标注Controller类，通过Eclipse启动项目，[访问](http://localhost:8080/index)