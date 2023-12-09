<div align="center">

# BA_calendar_e
![image](https://picst.sunbangyan.cn/2023/12/09/b7cedf5813c2c7b18a6c9e07746dc011.jpeg)


### 基于Kumiao二次开发框架的碧蓝档案插件
<img src="https://img.shields.io/badge/QQGroup-584380963-blue" alt="QQGroup">




</div>

# 📖 简介
一个(几乎)全能的BA机器人插件，集千里眼，总力战，定时推送日程表，模拟抽卡等众多功能为一体的多功能BA游戏小助手。且可同时与Yunzai，Nonebot，Mirai等众多框架同时使用。
本插件采用 GPL-3.0 license 协议开源<br>
# 📃 源码食用
本插件使用易语言编写，版本为5.9.<br>
本插件采用的Kumiao框架为2.3版本魔改框架，可保证后续的更新与兼容<br>
源码同时放出，可供自行修改
# 💻 安装
简易方便，无需配置环境，连接即可使用
<details open>
<summary>[推荐] 下载ZIP文件解压</summary>
  可下载release中的zip压缩包，也可使用提供的国内网盘文件

</details>
<details >
<summary>自行下载插件本体组装</summary>
  注意：仅方法仅供插件升级使用
</details>

**字体已与压缩包中给出，双击安装即可使用无需另行下载**

连接QQ机器人方法：https://www.yuque.com/staytomorrow/ba_calendar/rh5mime8o3xgb91l <br>
指南中仅列出了与官方机器人API以及Yunzai的连接方法，如需其他方法，可与作者私下了解<br>
由于作者懒狗，获取最新源码可加群或发送邮件至staytomorrow#qq.com<br>

# 💡 特别鸣谢
[ba.ganekee.com](https://ba.gamekee.com/)<br>
[bawiki-data](https://github.com/lgc-NB2Dev/bawiki-data)<br>
[鸡窝托斯古书馆](https://kivo.wiki/)<br>
[schaledb](https://schaledb.brightsu.cn/)<br>
[什亭之匣](https://arona.icu/)<br>
[anora api](https://doc.arona.diyigemt.com/api/)<br>
[Bluearchive-logo](https://github.com/nulla2011/Bluearchive-logo)<br>

# 📜 指令
## 指令介绍
### 普通菜单
| 指令名称 | 指令介绍 | 示例 |
| --- | --- | --- |
| ba菜单 | 获取机器人菜单 |  |
| ba十连 | 此命令为模拟十连抽卡命令，命令格式为ba十连+卡池名称* | ba十连爱丽丝 或 ba十连 爱丽丝 |
| ba一井 | 仅限群消息使用 | ba一井爱丽丝 或 ba一井 爱丽丝 |
| ba卡池列表 | 获取当前机器人存在的卡池名称，在抽卡时使用 |  |
| ba抽卡数据 | 获取本人当天抽卡数据（每日4点更新） |  |
| ba日服新闻 | 获取日服新闻列表 |  |
| ba服务器状态 | 获取游戏服务器当前状态 |  |
| ba总力战 | 获取日服总力战一图流 | ba总力战黑白 插件版本需≥20230605 |
| ba总力战国际 | 获取日服总力战一图流 | ba总力战国际黑白 插件版本需≥20230605 |
| ba日程表 | 获取日服日程表 |  |
| ba日程表国际服 | 获取国际服日程表 |  |
| ba猜老婆 | 开启猜老婆功能 |  |
| ba猜语音 | 开启猜语音功能 |  |
| 换图 | 当您正在猜老婆的时候，您可以使用此指令更换一张新图出来，具体情况依管理员设定而定 |  |
| ba好感度 | 查询您当前所有角色的好感度，好感度可通过猜老婆功能获取 |  |
| ba角评 | 获取角色评价(需更新Wiki数据后使用) | ba角评白子 |
| bawiki | 查询角色的WIKI信息 | bawiki白子 |
| ba生日 | 查询本周有哪些学生生日 |  |
| ba图片 | 查询一个角色的立绘、live2d、设定集 | ba图片白子 |
| ba关卡 | 查询某一关卡攻略 | ba关卡1-1 |
| ba搜索 | 模糊匹配所有攻略图 | ba搜索国际服总力战 ba搜索杂图可获取所有攻略图片名称 |
| balogo | 生成balogo图片：balogo 前半段 后半段 X偏移 Y偏移 -t(透明) | balogo 他能打 总力战吗  |
<br>
*：当开启不同设置时指令格式会有所不同

*****
#### 管理菜单
|  指令名称   |  指令介绍   | 示例 |
| --- | --- |---
|ba管理菜单|获取机器人管理菜单|
|ba添加推送群号     |   添加指定群允许被定时推送日程表  |ba添加推送群号114514
|ba移除推送群号|将指定群从定时推送日程表中删除|ba移除推送群号114514
|ba更改推送时间|更改定时推送日程表的时间|ba更改推送时间19（将日程表的推送时间设定在每日19点）
|ba更换总力战图片日服|更换日服总力战一图流的图片（仅限总力战数据来源为本地获取）|ba更换总力战图片日服+图片（注意图片和命令应在同一条消息内）
|ba更换总力战图片国际服|更换国际服总力战一图流图片|同上
|ba更换嘲讽图片|更换二星保底特殊提醒图片|ba更换嘲讽图片+图片（要求同上）
|ba更新学生wiki数据|更新学生wiki数据

#### 频道相关
**由于QQ频道的特殊性，频道数据与群数据不互通，指令也会有所差别**
普通菜单：QQ频道中不能使用ba一井功能，其他正常
管理菜单：管理命令完全不同，命令列表如下
|  指令名称   |  指令介绍   | 示例 |
| --- | --- |---
|ba管理菜单|获取机器人管理菜单|
| ba频道信息    |获取当前主频道id与子频道id以及个人id  （此命令无需管理员权限）   |
|ba绑定频道|允许机器人在此频道发言|
|ba解绑频道|不允许机器人在此频道发言|
|ba开启日程表推送|允许机器人在此频道内定时推送日服日程表|
|ba关闭日程表推送|禁止机器人在此频道内定时推送日服日程表|
|ba更改推送时间|介绍同管理菜单|ba更改推送时间19
|ba更新学生wiki数据|更新学生wiki数据
# ⚙️ 设置界面
<div align="center">
  
![image](https://github.com/staytomorrow/ba_calendar_e/assets/20775434/469be1a7-c2af-4e62-9842-d7c437ab711a)
  
![image](https://github.com/staytomorrow/ba_calendar_e/assets/20775434/e4769547-1a2e-4379-a29a-0a477dda769c)
  

</div>

# 📰 示例
TIP：仅在此列举部分内容，详细情况可移至语雀查看
>  ba十连+卡池名称（为空则默认为常驻池子）


![image](https://user-images.githubusercontent.com/20775434/167645774-b5098145-0cb8-4c01-a5e0-e84f9b29d58f.png)

>  ba卡池列表

列出所有卡池  
![image](https://user-images.githubusercontent.com/20775434/167646015-256a53a1-8c6a-4a61-8087-b7346d118491.png)

>  ba抽卡数据

列出你的抽卡数据<br>
![image](https://user-images.githubusercontent.com/20775434/167646201-d6d3a73b-f8d6-4df5-8a39-3a5c4d1c84b7.png)

>  ba总力战一图流

总力战一图流<br>
![image](https://user-images.githubusercontent.com/20775434/167646506-d891c4cb-3c57-4f3e-9f85-ce40876a9137.png)
<br>
（这个功能的实现有点暴力，借鉴了同类插件的获取方法，但是我用的是nga的数据，获取的图片可能有误）
>  ba时刻表

推送活动，来源bwiki<br>

![LO3TDU9U(Q9FVHJ3C5LP6 W](https://user-images.githubusercontent.com/20775434/167648768-e19f1e03-ca6b-46bd-a7ba-13955f302e8f.png)


