# 0day-capture

正值护网时期，你是不是正缺少一个0day捕获的工具呢？快来下载试试吧～～

# # 使用方法

 文件目录

```
servers.py 						服务脚本

request_params.log 		访问日志

	Templates   					模版目录
	index.html 						模版文件
```

使用chrome插件SingleFile下载要复制的网页，保存为index.html放至Templates目录下

<img width="354" alt="image-20240708135432229" src="https://github.com/1ighttack/0day-capture/assets/71672296/affbd41a-e988-463b-aca0-926e1fb276ed">


Python3 servers.py

<img width="302" alt="image-20240708144937952" src="https://github.com/1ighttack/0day-capture/assets/71672296/0eeb7c32-1f9d-43f3-badf-2edd1b379745">


访问诱捕页面

<img width="1263" alt="image-20240708145014534" src="https://github.com/1ighttack/0day-capture/assets/71672296/caffd6dc-8445-4a9e-b5b5-e3bd56f09c08">


使用zan8in师傅的afrog测试

<img width="525" alt="image-20240708145214997" src="https://github.com/1ighttack/0day-capture/assets/71672296/d8989ad9-77f1-48b5-b0e6-4042f8b705a2">


日志内会完整记录红队的访问时间、ip、路径、请求头、请求体

<img width="1757" alt="image-20240708145809781" src="https://github.com/1ighttack/0day-capture/assets/71672296/b8457c8a-1965-4546-9405-a0b2e74e776e">


剩下只需要处理下数据即可
