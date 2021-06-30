# heliosman<汇联易中控增强插件>
## 功能说明
汇联易中控增强插件旨在帮助第三方系统与汇联易集成，将第三方系统集成所需信息快速、便捷的展示给集成开发者。汇联易中控增强插件仅仅处理当前登录账号有权限访问数据并基于汇联易开放接口处理并展示数据。插件运行过程中不收集任何数据。插件已开放功能如下：
1. 查看当前用户所在租户的租户ID和租户名称(在集成过程中各种问题处理都会用到租户ID)。
2. 查看当前租户OPEN API调用秘钥(需要管理员账号)。
## 安装步骤
汇联易中控增强插件基于油猴(Tampermonkey)开发，可以运行在任何可以安装油猴的浏览器上，建议使用Chrome，脚本安装步骤以Chrome浏览器为例：
1. 在Chrome应用商店中搜索"Tampermonkey"并安装油猴应用(需要科学上网，不能科学上网请看步骤2)
![alt 应用商店安装油猴](https://github.com/swyrzsyf/heliosman/material/m1.jpg)
2. 如果不能科学上网，可以下载油猴离线安装包，并将安装包拖到Chrome浏览器中即可。
[油猴离线安装包](https://github.com/swyrzsyf/heliosman/material/extension_4_13_0_0.crx)
3. 访问[Greasy Fork](https://greasyfork.org/zh-CN)，在Greasy Fork中搜索heliosman，
## 功能开发计划
计划开发功能如下，如有建议增加的功能，你可以发送邮件到swyrzsyf@protonmail.com，我们将认真考虑你建议的功能。
1. 中控单据列表页面直接查看单据OPEN API返回报文。

