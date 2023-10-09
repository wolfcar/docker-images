# docker-images
## 设置docker 网络


```shell
docker network create --gateway 172.22.0.1 --subnet 172.22.0.0/16 dev
```

## 各环境id
|  容器   |  ip   |  依赖 | 暴露端口 |
| --- | --- | --- |
|  mysql   |   172.22.0.5  |  3306   |
|  nacos   |  172.22.0.6   |  8848   |
|  apollo  | 172.22.0.7    | 8070 8090 8080    |
|     |     |     |
|     |     |     |
|     |     |     |
|     |     |     |
|     |     |     |