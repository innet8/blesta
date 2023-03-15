# .env 环境变量
>cp .env.example .env
```
#blesta的文件路径
WEB_PATH=./blesta

#MySQL版本和php版本
MYSQL_VERSION=5.7
PHP_VERSION=7.4

#nginx的端口和php服务端口
NGINX_PORT_HTTP=80
NGINX_PHP_UPSTREAM_CONTAINER=php-fpm
NGINX_PHP_UPSTREAM_PORT=9000

#数据库信息填写
MYSQL_DATABASE=test
MYSQL_USER=test
MYSQL_PASSWORD=test
MYSQL_PORT=3306
MYSQL_ROOT_PASSWORD=test
```
# 启动
```
sudo docker-compose up -d
```

# 安装
>推荐使用第二种方法进行安装，进入php容器执行，可以看到执行过程。
![image](https://user-images.githubusercontent.com/85656971/225224010-e134bd86-38e9-45ad-b558-e1730b73152f.png)
