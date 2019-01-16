# docker-hello-world
Hello World! (an example of minimal Dockerization)

## 编译镜像
```bash
docker build -t hello-world .
```

## 镜像命名
```bash
docker tag hello-world vwarship/hello-world:latest
```

## 上传镜像
```bash
docker push vwarship/hello-world:latest
```

## 运行容器
```bash
docker run -p 5000:80 vwarship/hello-world:latest
```

## 访问应用
```txt
打开浏览器，访问网址：http://localhost:5000

Hello World!

Hostname: 86fcc9672e04
IP: 172.17.0.2
```
