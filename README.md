## Hana-L4D2-Plugins

|                            插件名                            |                         说明                          |
| :----------------------------------------------------------: | :---------------------------------------------------: |
| [player_fakelag](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/player_fakelag) |       Player Fakelag / 玩家延迟控制 / 平衡延迟        |
| [aim_monitor](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/aim_monitor) |                Aim Monitor / 瞄准监控                 |
| [hide_server](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/hide_server) |               Hide Server / 隐藏服务器                |
| [l4dffannounce](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/l4dffannounce) |              ff announce / 友伤[杀]提示               |
| [sourcetvsupport](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/sourcetvsupport) |           sourcetvsupport / 服务器录制demo            |
| [l4d2_si_highlights](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/l4d2_si_highlights) |           l4d2_si_highlights / 特感多控提示           |
| [l4d2_MultiplayerVersus](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/l4d2_MultiplayerVersus) |        l4d2_MultiplayerVersus / 对抗多v多用的         |
| [l4d_tank_damage_announce](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/l4d_tank_damage_announce) | l4d_tank_damage_announce / 好看一点适配多人的集火播报 |

## Plugins / 插件列表

### 1. Player Fakelag / 玩家延迟控制 -[ProdigySim &amp; Bred](https://github.com/ProdigySim/custom_fakelag)

在大红的基础上完全重写平衡逻辑只能说究极完善版

#### Commands / 命令:

* sm_fakelag `<player>` `<ms>` - Set fake lag for a player (0-400ms) / 设置玩家的假延迟(0-400ms)
* sm_myfl `<ms>` - Set your own fake lag / 设置自己的假延迟
* sm_efl - Vote to equalize all players' ping / 投票平衡所有玩家ping值
* sm_cfl - Vote to cancel ping equalization / 投票取消ping值平衡
* sm_tefl - Vote to equalize team pings / 投票平衡团队ping值
* sm_fcfl - Admin force to cancel ping equalization / 管理员强制取消ping值平衡
* sm_fefl - Admin force to equalize player pings / 管理员强制平衡玩家ping值

### 2. Aim Monitor / 瞄准监控

监控某些玩家获取瞄准数据用于和demo以及其他记录人工审查

可能逻辑上还有漏洞,需大量数据改进

Features / 功能:

* 追踪玩家瞄准移动和射击模式
* 监控爆头、伤害和击杀数据
* 基于多个因素计算瞄准分数
* 记录可疑活动
* 管理员命令用于开始/停止监控特定玩家

#### Commands / 命令:

* sm_monitor `<player>` -  开始监控玩家
* sm_mt `<player>` -  monitor命令的简写
* sm_unmonitor `<player>` -  停止监控玩家
* sm_unmt `<player>` -  unmonitor命令的简写

### 3. Hide_server / 隐藏服务器

自动切换服务器标签,隐藏服务器

Features / 功能:

* 玩家数量满足survivor_limit*2后将tags切换为hidden

#### Commands / 命令:

* sm_hp - 恢复所有生还者生命值
* 其他打开你的admin菜单就有咧

### 4. l4dffannounce / 友伤提示

字面意思,友伤提示.

Features / 功能:

* 给傲娇的你和傲娇的队友精确播报来自队友的爱

#### Commands / 命令:

* ConVar :  l4d_ff_announce_enable 0/1		开启关闭

### 5. sourcetvsupport / 服务器demo录制 - [shqke](https://github.com/shqke/sourcetvsupport)

服务器自动录制demo,除了看不见手臂外其他都比较OK

自动录制插件改动较大，并且仅针对于使用readyup的对抗服务器 原插件 - [shqke](https://github.com/shqke/sp_public/tree/master/autorecorder)

Features / 功能:

* 在开始时自动录制demo,该demo可以查看所有人视角,等于你在旁观
* 提供人性化的php下载页和自动处理脚本但是需要大量改动适配自己服务器
* 非常吃性能,性能不够的服务器不建议采用

#### Commands / 命令:

* sm_recordstatus		查看sourcetv状态

### 6. l4d2_si_highlights / 特感高光操作

Features / 功能:

* 提示坦克一拍N 牛一撞N Boomer一喷N 丢石头命中 打铁命中 多控提示

#### Commands / 命令:

* 无

### 7. l4d2_MultiplayerVersus / 多v多

Features / 功能:

* 对抗多v多，并且支持多克生成

#### Commands / 命令:

* 无
