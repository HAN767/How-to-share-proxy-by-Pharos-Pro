##### 准备

- wifi网络环境下，手机需要保证SS、SSR或Trojan代理正常访问
- 获取手机连接Wifi的IP地址, 如: 192.168.10.10，在iOS设置中wifi的详情页中。
- Win/Mac chrome已经安装SwitchyOmega



##### Pharos HTTP代理连接Info

```
格式：
IP：xx.xx.xx.xx 
端口: 7777


示例：
IP: 192.168.10.10
Port: 7777
```



##### Win/Mac启用代理

```
(1) 打开Chrome -- 点击SwitchyOmega插件配置 -- 点击【左侧】新建情景模式 -- 情景模式名称: [自定义]；情景模式类型选择“代理服务器” -- 点击“创建”

(2) 【左侧】点击刚刚创建的HTTP情景模式 -- 代理协议选择“HTTP” -- 代理服务器输入“192.168.10.10” -- 代理端口输入“7777” -- 点击左下角“应用选项”

(3) 右上角点击SwitchyOmega插件 -- 点击刚刚配置好的HTTP代理名称[名称是自定义的] -- 访问Google 
```




