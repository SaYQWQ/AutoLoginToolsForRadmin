# AutoLoginToolsForRadmin
## 用于Radmin的自动登录器，基于win32，通过cmd拉起程序并模拟键盘输入实现
### 使用方式
1. 将程序放入Radmin程序所在的文件夹。
2. 打开程序，在地址栏输入ip（端口可选，默认4899），点击右侧按钮连接。
4. 支持使用保存密码直接登录或临时指定登录。
### 注意事项
1. 第一次使用需要先输入需要的内容，更新一次记录文件，以生成默认密码。
2. 目前程序只能同时一个连接被使用，发起新连接前请先关闭旧连接窗口。
3. 目前程序能发起完全控制，后续会添加其他连接选项。
4. 目前仅能保留一个默认密码，且配置文件中为明文保存，如有需要请自己做好保密工作。后续会对其优化。
