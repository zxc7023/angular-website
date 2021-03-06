![node_11](https://img.shields.io/badge/node.js-v11.4.0-green?logo=node.js)
![angular](https://img.shields.io/badge/angular-v8.0.3-red?logo=angularjs)
![typescript](https://img.shields.io/badge/typescript-latest-blue?logo=typescript)

# angular2로 website 만들기 프로젝트

### 0. 개요
- Angular Front Framework를 사용하여 기본적인 웹사이트를 Step by Step으로 만들어 나가는 프로젝트
- BackEnd Resource 서버는 SpringBoot2 RESTful api를 이용 
    - https://daddyprogrammer.org/post/series/springboot2-make-rest-api/
- daddyprogrammer.org에서 강의 내용 연재하고 있으며 Github로 소스 공개
    - https://daddyprogrammer.org/post/series/spring-rest-api-angular-framework-make-website/

### 1. 개발환경
- Angular CLI: 8.0.6
- Node: 11.4.0
- Angular: 8.0.3
- Visual Studio Code

### 2. 프로젝트 실행
- SpringBoot API Run
    - http://localhost:8080
    - Swagger: http://localhost:8080/swagger-ui.html
- Angular Install
    - npm install -g @angular/cli
- Angular Run
    - npm install ( run only once )
    - npm start
    - http://localhost:4200
    
### 3. 목차
- Spring Rest api + Angular framework로 웹사이트 만들기(1) – 프로젝트 구성 및 반응형 레이아웃 구현
    - Document
        - https://daddyprogrammer.org/post/6237/rest-api-angular-framework-make-website/
    - Git
        - https://github.com/codej99/angular-website/tree/feature/initializelayout
- Spring Rest api + Angular framework로 웹사이트 만들기(2) – 로그인/가입 구현
    - Document
        - https://daddyprogrammer.org/post/6433/spring-rest-api-angular-framework-signin-siginup/
    - Git
        - https://github.com/codej99/angular-website/tree/feature/signup-signin-authentication
- Spring Rest api + Angular framework로 웹사이트 만들기(3) – 내정보, Interceptor, Router Guard 구현
    - Document
        - https://daddyprogrammer.org/post/6667/spring-rest-api-angular-framework-myinfo-authguard/
    - Git
        - https://github.com/codej99/angular-website/tree/feature/myinfo-authguard
- Spring Rest api + Angular framework로 웹사이트 만들기(4) - 게시판(CRUD)
    - Document
        - https://daddyprogrammer.org/post/6785/spring-rest-api-angular-framework-make-board-crud/
    - Git
        - https://github.com/codej99/angular-website/tree/feature/board
- Spring Rest api + Angular framework로 웹사이트 만들기(5) – 개선사항 적용 (custom alert/confirm dialog, resolve, 404page)
    - Document
        - https://daddyprogrammer.org/post/7025/spring-rest-api-angular-framework-custom-alert-confirm-resolve/
    - Git
        - https://github.com/codej99/angular-website/tree/feature/improvement        
- Spring Rest api + Angular framework로 웹사이트 만들기(6) – 개선사항 적용 (loading spinner)
    - Document
        - https://daddyprogrammer.org/post/7198/spring-rest-api-angular-framework-loading-spinner/
    - Git
        - https://github.com/codej99/angular-website/tree/feature/loading-spinner  
