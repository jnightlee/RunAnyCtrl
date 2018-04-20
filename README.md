# 【RunAnyCtrl】自由控制软件自动启动 v1.4.18

设定足够灵活的规则，在不同的使用场景下自动智能地启动不同的软件和应用，这是我开发这个软件的初衷😁

**RunAnyCtrl跟OneDrive之类同步网盘搭配更佳，让你电脑了解你的上班、学习、娱乐各种情景！随你心意**


同时RunAnyCtrl也可以做为一个AHK脚本的集中管理器

> （RunAnyCtrl是AHK脚本，需要先在系统中安装AutoHotkey软件，才能启动，下载地址：[https://autohotkey.com](https://autohotkey.com) ）

---

## RunAnyCtrl使用场景

- **早上到公司按下开机：** 泡杯咖啡，电脑启动后已经自动打开了早间新闻(小于10点)、TIM、工作软件、更换了最新的桌面壁纸等等
- **晚上回家后按下开机：** 电脑自动播放音乐，并且浏览器打开了视频网站(打开对应星期几更新的剧)、登录了QQ、游戏等等

- **星期一，但是今天是节假日不上班：** 自动启动娱乐软件
- **周末，但是电脑连接的网络是公司网络：** 今天加班，自动打开工作软件

- **无网络情况：** 不自动运行任何需要网络的应用

---

## RunAnyCtrl使用说明

![RunAnyCtrl使用说明](https://raw.githubusercontent.com/hui-Zz/RunAnyCtrl/master/RunAnyCtrl使用说明.png)

---
## RunAnyCtrl现有规则表

| 公共规则                                                  | 参数                                                         | 时间规则                 | 参数                                         |
| :-------------------------------------------------------- | ------------------------------------------------------------ | ------------------------ | -------------------------------------------- |
| 无条件真和假                                              | 用于循环执行等特殊情况                                       | 验证星期几               | (1-7)，1表示星期天                           |
| 判断启动项当前是否已经运行                                | 进程名或者启动项路径                                         | 验证指定时间点           | （00-23）小时                                |
| 验证网络是否连接正常                                      | 网络测试网址，<br />不传默认用百度做为测试站点               | 通过第三方接口验证节假日 | 验证的日期20180418，<br />不传默认为当天日期 |
| 验证当前连接的Wifi名称<br />（命令执行，会闪一下命令框）  | wifi名称                                                     |                          |                                              |
| 验证当前连接的Wifi名称<br />（后台静默写入bat执行后删除） | wifi名称                                                     |                          |                                              |
| 验证当前电脑名称                                          | 电脑名                                                       |                          |                                              |
| 验证当前登录用户名称                                      | 用户名                                                       |                          |                                              |
| 验证当前登录用户有管理员权限                              |                                                              |                          |                                              |
| 验证当前windows系统版本                                   | 系统版本号如：WIN_7, WIN_8, WIN_VISTA, WIN_2003, WIN_XP, WIN_2000, <br />Windows10版本为具体的版本号数字 |                          |                                              |
| 验证当前当操作系统为64位                                  |                                                              |                          |                                              |
| 验证当前内网ip地址                                        | ip（模糊匹配）                                               |                          |                                              |
| 验证当前外网ip地址                                        | ip（模糊匹配）                                               |                          |                                              |
| 验证当前ip地址定位的省市地址                              | 城市名、省名                                                 |                          |                                              |
| 验证当前网络运营商                                        | 运营商名，如中国电信：China Telecom                          |                          |                                              |

---

**你的支持是我最大的动力！金额随意**

**在此特别感谢 AHK-工兵等对RunAnyCtrl的大力支持，欢迎大家多多提出建议！**



![支付宝](https://raw.githubusercontent.com/hui-Zz/RunAny/master/支持RunAny.jpg)
