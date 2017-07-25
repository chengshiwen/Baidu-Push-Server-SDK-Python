百度云推送服务端SDK Python版本
==============

将百度云推送（Push）服务端的所有 API 封装成一个类 `Channel.py`，通过对该类的简单初始化，即可调用其内部的各种方法，使用百度云推送服务。

`Channel.py` 提供的方法和服务端 API 对应，是对服务端 REST API 的封装，详细的 REST API 请参考[官网API列表](http://push.baidu.com/doc/restapi/restapi)。


### 代码构成

*   `Channel.py` -- SDK 脚本，包含对外提供的所有接口
*   `sample/sample.py` -- 使用 SDK 的 Demo 文件


### 依赖库

*   [requests](http://python-requests.org)


### 一般规则

*   所有函数的参数和返回值中如果有中文，必须是UTF-8编码
*   不需要对函数参数进行urlencode
*   错误信息见 [错误码定义](http://push.baidu.com/doc/restapi/error_code)


### 版本更迭

该 Python SDK 主要由 [luvchh](https://github.com/Argger) 完成了大部分的工作

**第一版：**

由[luvchh](https://github.com/Argger) 提供，并开放在 Github 上：<https://github.com/Argger/pusher_python_sdk>

**第二版：**

由[blacklaw0](https://github.com/blacklaw0) 修改，Github 地址：<https://github.com/blacklaw0/pusher_python_sdk>

**第三版：**

由 [gfreezy](https://github.com/gfreezy) 修改，Github 地址：<https://github.com/gfreezy/pusher_python_sdk>

**第四版：**

由 [chengshiwen](https://github.com/chengshiwen) 更新，Github 地址：<https://github.com/chengshiwen/Baidu-Push-Server-SDK-Python>
