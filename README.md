# Cerebro Image

## 使用方式

启动

```bash
$ docker run -d --name cerebro -p 9000:9000 liulik/cerebro:v0.9.4
# 自定义端口
$ docker run -d --name cerebro -e CEREBRO_PORT=8080 -p 8080:8080 liulik/cerebro:v0.9.4
```

访问

```
http://127.0.0.1:9000
```

其他参考官方代码仓库：[Github · lmenezes/cerebro](https://github.com/lmenezes/cerebro)
