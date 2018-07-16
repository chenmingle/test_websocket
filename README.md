# 一个高并发的websocket脚本


## 根据最近公司上线一个直播项目，但是有一天测试那边一脸苦逼的来找到我，问我有什么好工具可以实现高并发的测试，他使用jmeter限制了400个并发数（个人没去研究过不知道是否真的限制），后来我第一时间想到python写一个脚本，也没想多小就答应帮他搞一个测试脚本。


### 首先整理思：
* 要实现高并发不到两点
	* 多进程
	* 多线程
	
### 首先安装先要环境：
```
pip install websocket
pip install threadpool
pip install websocket-client
pip install multiprocessing
```


### 执行脚本：
```
python test_websocket.py
```



