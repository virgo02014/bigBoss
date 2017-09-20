## bigBoss

#### [virgo](https://virgo9.github.io/)
#### [leo](https://leo2vip.github.io/)

## 项目运行

#### Vue 不支持 IE8 及其以下版本，因为 Vue.js 使用了 IE8 不能模拟的 ES5 特性。
#### Vue.js 支持所有兼容 ECMAScript 5 的浏览器。

``` bash
# clone project
git clone https://github.com/Virgo9/bigBoss.git

# project configuration
cd bigBoss-web/bigBoss-web-api/src/main/webapp/public/
    npm install [初次需要执行]
    npm run build

# start tomcat

```

## 项目布局

```
.
├── bigBoss-back                                      // 
│   ├── bigBoss-back-api                              // 
│   ├── bigBoss-back-bean                             // 
│   ├── bigBoss-back-dao                              // 
│   ├── bigBoss-back-service                          // 
│   ├── bigBoss-back.iml                              // 
│   ├── pom.xml                                       // 
├── bigBoss-web                                       // 
│   ├── bigBoss-web-api                               // 
│   │   ├── src                                       //
│   │   │   ├── main                                  //
│   │   │   │   ├── java                              //
│   │   │   │   ├── resources                         //
│   │   │   │   ├── webapp                            //
│   │   │   │   │   ├── public                        //
│   │   │   │   │   │   ├── node_modules              // npm 加载的项目依赖模块
│   │   │   │   │   │   ├── src                       // 要开发的目录(图片 组件 核心文件等)
│   │   │   │   │   │   ├── package.json              // 项目配置文件
│   │   │   │   │   ├── WEB-INF                       //
│   │   │   │   │   │   ├── web.xml                   //
│   │   │   │   │   ├── index.jsp                     //
│   │   ├── target                                    //
│   ├── bigBoss-web-common                            // 
│   ├── bigBoss-web.iml                               // 
│   ├── pom.xml                                       // 
├── bigBoss.iml                                       // 
├── pom.xml                                           // 
.
```
