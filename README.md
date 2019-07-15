# CISCN 2019 华东南 Web4

## 题目详情

- **2019 CISCN 2019 华东南 Web4**

## 感谢
华东南赛区的南溟师傅备份题目并提供给我复现。

## 考点

- 任意文件读取
- 伪随机数

## 启动

	docker-compose up -d
	open http://127.0.0.1:8083/

## WriteUp

1. http://web55.buuoj.cn/read?url=app.py 读源码
2. http://web55.buuoj.cn/read?url=/sys/class/net/eth0/address 读网卡地址
3. 用 exp 下面的脚本来算出 SECRET_KEY，并重新签名。（Python2，和靶机一致）
4. 置 session Cookie，访问 http://web55.buuoj.cn/flag

## 版权

该题目复现环境尚未取得主办方及出题人相关授权，如果侵权，请联系本人删除（ i@zhaoj.in ）
