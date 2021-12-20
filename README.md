# yiblog-backend
This is a demo for CSUN-COMP586 Object-oriented programming.

Demo shown at: http://54.177.15.182
Swagger-ui: http://54.177.15.182:8081/swagger-ui/index.html

**Frontend:** Vue.js

**Backend:** SpringBoot+Mybatis plus+Redis

**SPA:** This is a SPA project

**Authentication:** Users can log up and login (JWT) to view and edit the blogs.

**MVC on the server with routing & ORM:** There is a js file to manage the routing to contact with background. 
like "/blogs" is mapping to @GetMapping("value=/blogs") in Java methods. 

**Dependency Ingection:** Springboot annotation -> implement dependency injection, like @Data, @Components, @RestController etc.

**Authorization:** Users can only edit their own blog. 

**Unit Testing:** build-in swagger

**4 tables:**
"user","blog","comment","blog_comment_detail".
There are 4 controllers, and they all have associated mapping annotations to interact with the front-end. (easyblog-backend/src/main/java/com/yiblog/controller) 
![image](https://user-images.githubusercontent.com/52452350/144959606-b6c1f643-6d37-44c8-ad38-a9df13e118ea.png)
