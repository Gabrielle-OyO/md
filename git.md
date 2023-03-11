



python安装库报错：

```
raise ValueError("check_hostname requires server_hostname")
ValueError: check_hostname requires server_hostname
```

![image-20230310124145986](C:/Users/hp/AppData/Roaming/Typora/typora-user-images/image-20230310124145986.png)

![image-20230310124233387](C:/Users/hp/AppData/Roaming/Typora/typora-user-images/image-20230310124233387.png)

最大一个原因就是网络问题

关闭全部代理设置，加上镜像源    pip install -r requirements.txt  -i https://mirrors.aliyun.com/pypi/simple/

![image-20230310124355590](C:/Users/hp/AppData/Roaming/Typora/typora-user-images/image-20230310124355590.png)



