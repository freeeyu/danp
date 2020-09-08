# danp
docker+alpine+nginx+php轻量化php环境镜像,增加了alpine的阿里云源,增加了一些laravel必须的扩展安装命令。

### 使用方法
1. `docker build -t myimage .`

2. `mkdir /wwwroot/mybase`
 
3. `docker run -d --name mysite -p 80:8080 -v /wwwroot/mybase:/var/www/html myimage`

4. 将代码放入目录/wwwroot/mybase

### 更新镜像
docker pull freeeyu/dnmp:v1

### 其他注意事项
查看原作者:[https://github.com/TrafeX/docker-php-nginx](https://github.com/TrafeX/docker-php-nginx)
