## 启动命令（每次更新代码也要重启）

```bash
# 启动 gewe
$ docker compose -f docker-compose.yml down
$ docker compose -f docker-compose.yml up -d
```

```bash
$ cd docker
# 启动 dify-on-wechat (重命名)
$ docker compose -p dify-on-wechat -f docker-compose.yml down
$ docker compose -p dify-on-wechat -f docker-compose.yml up -d
```