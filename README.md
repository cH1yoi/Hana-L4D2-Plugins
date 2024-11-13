## Hana-L4D2-Plugins

|                            插件名                            |                   说明                   |
| :----------------------------------------------------------: | :--------------------------------------: |
| [player_fakelag](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/player_fakelag) | Player Fakelag / 玩家延迟控制 / 平衡延迟 |
| [aim_monitor](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/aim_monitor) |          Aim Monitor / 瞄准监控          |
| [admin_hp_spawn](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/admin_hp_spawn) |  Admin HP & Spawn / 管理员生命值与重生   |
| [l4dffannounce](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/l4dffannounce) |        ff announce / 友伤[杀]提示        |

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

### 3. Admin HP & Spawn / 管理员生命值与重生

就是权限🐕用的,idk

Features / 功能:

* 恢复单个或者全体血量,复活寄了的玩家在你准心处,并且集成在admin菜单里

#### Commands / 命令:

* sm_hp - 恢复所有生还者生命值
* sm_givehp [player] - 恢复指定玩家生命值
* sm_respawn [player] - 重生指定玩家

### 4. l4dffannounce / 友伤提示

字面意思,友伤提示.

Features / 功能:

* 给傲娇的你和傲娇的队友精确播报来自队友的爱

#### Commands / 命令:

* ConVar :  l4d_ff_announce_enable 0/1		开启关闭
