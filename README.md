
##### 安装依赖

```
npm install 
```


##### 开发模式

```
npm run serve
```

运行之后，访问地址：http://localhost:8081

##### 生产环境打包

```
npm run build
```



##### node sass 安装出现问题：

```
npm set sass_binary_site http://cdn.npm.taobao.org/dist/node-sass
```

https://juejin.cn/post/6946530710324772878



##### node 版本 

12及以上



##### nginx 前端打包配置



```

    server {
        listen 8083;
        server_name localhost; # Adjust as needed

       
		location / {
            root   C:/nginx/html/airmonitor;
			try_files $uri $uri/ /index.html;
            index  index.html index.htm;
        }
    }
```

