# spring-thyleaf-demo
* 前置作業
* thyleaf配置
* Demo

**A. 前置作業**  
---
專案引用: https://github.com/st801026bill/spring-localcache-demo

**B. thyleaf配置**  
---
### 1. thyleaf & devtool 基本配置
**Dependency**
```sql
<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-thymeleaf</artifactId>
</dependency>
<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-devtools</artifactId>
  <scope>runtime</scope>
  <optional>true</optional>
</dependency>
```
**Devtool啟用設定**  
intellij idea 啟用後端自動重啟
![image](https://github.com/st801026bill/spring-thymeleaf-demo/blob/master/image/devtool1.png)
![image](https://github.com/st801026bill/spring-thymeleaf-demo/blob/master/image/devtool2.png)

chrome 安裝 livereload 啟用前端自動刷新
![image](https://github.com/st801026bill/spring-thymeleaf-demo/blob/master/image/livereload.png)

### 2. thyleaf 基本語法
參考 https://www.thymeleaf.org/index.html


**C. Demo**  
---  
1. open broswer & enter`http://localhost:9000/thymeleaf/todoList`
![image](https://github.com/st801026bill/spring-thymeleaf-demo/blob/master/image/thymeleaf.png)
