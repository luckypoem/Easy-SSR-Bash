![][1]
![][2]

# 安装脚本
（请使用 **Xshell** 连接以取得最好的**中文编码**支持）  

``` vim
wget -N --no-check-certificate https://raw.githubusercontent.com/Moexin/Easy-SSR-Bash/master/install.sh && bash install.sh
```
安装完成后输入 **ssr** 回车即可使用
# 卸载脚本

``` vim
wget -N --no-check-certificate https://raw.githubusercontent.com/Moexin/Easy-SSR-Bash/master/uninstall.sh && bash uninstall.sh
```
# 系统支持

 - Ubuntu 14
 - Ubuntu 16
 - CentOS 6
 - CentOS 7
 - Debian 7
 - Debian 8（推荐）

# 功能介绍

 - 一键开启、关闭SSR服务
 - 添加、删除、修改用户端口和密码
 - 自由限制用户端口流量使用
 - 自动修改防火墙规则
 - 自助修改SSR加密方式、协议、混淆等参数
 - 自动统计，方便查询每个用户端口的流量使用情况
 - 自动安装Libsodium库以支持Chacha20等加密方式
 - 每月自动清空用户流量
 - 一键封禁BT下载、垃圾邮件发送功能。（感谢逗比大佬提供）

# 已知问题

 - 最后一名用户无法删除
 - 部分系统上IP地址识别错误，导致SSR链接生成有问题，手动修改即可。

# 常见问题
问1：是否需要自己先安装SSR服务端？

答1：不需要，脚本默认自带了安装SSR的部分。请使用**纯净**的系统进行安装。

问2：是否能和**Oneinstack**一起安装？

答2：原则上是可以的，但是并不建议放在生产环境中使用，建议单独使用一台VPS来扶墙。

问3：为什么无法开启兼容模式？

答3：因为SSR服务端只支持部分协议的兼容设置，所以并非所有的协议插件都能兼容原版。具体列表参考 SSR协议插件稳文档

问4：脚本安装好连接上没有网络？

答4：请确认好您已经正确填写了加密方式、协议和混淆，并且使用最新的SSR客户端而不是SS客户端。

问5：脚本还是无法使用！

答5：如果可以输入 ssr 命令打开功能菜单，请选择 1 服务管理 再选择 4 查看日志。发送给我详细截图以解决问题。

问6：脚本是否支持 UDP 转发？

答6：默认是开启了 UDP转发的，如果无法使用，请检查SSR官方文档修改本地配置，SSR服务端默认安装在 /usr/local/shadowsocksr

  [1]: http://imglf.nosdn.127.net/img/cEczVHlUNlVvWHlYdzBGQ1V6dk0zSGFXY1c3NmtjTkc1YSt5anljTjZnYWVQOUI5NzlBVndnPT0.png?imageView&thumbnail=1680x0&quality=96&stripmeta=0&type=jpg%7Cwatermark&type=2&text=wqkgbG1lb28uY29tIC8gaW1nLWxtZW9vLmxvZnRlci5jb20=&font=bXN5aA==&gravity=southwest&dissolve=30&fontsize=340&dx=16&dy=20&stripmeta=0
  [2]: http://imglf0.nosdn.127.net/img/cEczVHlUNlVvWHlYdzBGQ1V6dk0zTzh0cVg5NEJkQUNsT25oRE9oUjByVmd4c3dibFdVV2pnPT0.png?imageView&thumbnail=1680x0&quality=96&stripmeta=0&type=jpg%7Cwatermark&type=2&text=wqkgbG1lb28uY29tIC8gaW1nLWxtZW9vLmxvZnRlci5jb20=&font=bXN5aA==&gravity=southwest&dissolve=30&fontsize=340&dx=16&dy=20&stripmeta=0