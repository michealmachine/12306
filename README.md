# 12306
### 启动步骤
安装 MySQL 5.7.36
- 如果你是Windows、Linux 以及 Mac Intel 用户通过以下 Docker 命令启动 MySQL 实例：
```
docker run --name mysql \
-p 3306:3306 \
-e MYSQL_ROOT_HOST='%' \
-e MYSQL_ROOT_PASSWORD=root \
-d mysql:5.7.36
```
- 如果你是 Mac M1 用户通过以下 Docker 命令启动 MySQL 实例：
```
docker run --name mysql \
--platform=linux/amd64 \
-p 3307:3306 \
-e MYSQL_ROOT_HOST='%' \
-e MYSQL_ROOT_PASSWORD=root \
-d amd64/mysql:5.7.36
```
