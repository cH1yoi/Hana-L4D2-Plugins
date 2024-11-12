## Hana-L4D2-Plugins

| 插件名                                                                              | 说明                                     |
| ----------------------------------------------------------------------------------- | ---------------------------------------- |
| [player_fakelag](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/player_fakelag) | Player Fakelag / 玩家延迟控制 / 平衡延迟 |
| [aim_monitor](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/aim_monitor)       | Aim Monitor / 瞄准监控                   |
| [admin_hp_spawn](https://github.com/cH1yoi/Hana-L4D2-Plugins/tree/main/admin_hp_spawn) | Admin HP & Spawn / 管理员生命值与重生    |

## Plugins / 插件列表

### 1. Player Fakelag / 玩家延迟控制 -[ProdigySim &amp; Bred](https://github.com/ProdigySim/custom_fakelag)

Allows management of artificial latency for balancing gameplay.

允许管理人工延迟以平衡游戏。

Features / 功能:

* Set custom latency per player / 为每个玩家设置自定义延迟
* Team-based ping balancing / 基于团队的ping值平衡
* Voting system for ping equalization / ping值均衡化投票系统
* Admin force commands for ping management / 管理员强制ping管理命令

#### Commands / 命令:

* sm_fakelag `<player>` `<ms>` - Set fake lag for a player (0-400ms) / 设置玩家的假延迟(0-400ms)
* sm_myfl `<ms>` - Set your own fake lag / 设置自己的假延迟
* sm_efl - Vote to equalize all players' ping / 投票平衡所有玩家ping值
* sm_cfl - Vote to cancel ping equalization / 投票取消ping值平衡
* sm_tefl - Vote to equalize team pings / 投票平衡团队ping值
* sm_fcfl - Admin force to cancel ping equalization / 管理员强制取消ping值平衡
* sm_fefl - Admin force to equalize player pings / 管理员强制平衡玩家ping值

### 2. Aim Monitor / 瞄准监控

A tool for administrators to monitor player aim behavior and detect potential cheating.

一个供管理员监控玩家瞄准行为并检测潜在作弊的工具。

Features / 功能:

* Track player aim movements and shooting patterns / 追踪玩家瞄准移动和射击模式
* Monitor headshots, damage, and kill data / 监控爆头、伤害和击杀数据
* Calculate aim scores based on multiple factors / 基于多个因素计算瞄准分数
* Log suspicious activities / 记录可疑活动
* Admin commands to start/stop monitoring specific players / 管理员命令用于开始/停止监控特定玩家

#### Commands / 命令:

* sm_monitor `<player>` - Start monitoring a player / 开始监控玩家
* sm_mt `<player>` - Shorthand for monitor command / monitor命令的简写
* sm_unmonitor `<player>` - Stop monitoring a player / 停止监控玩家
* sm_unmt `<player>` - Shorthand for unmonitor command / unmonitor命令的简写

### 3. Admin HP & Spawn / 管理员生命值与重生

Provides administrators with health management and respawn capabilities through menus.

通过菜单为管理员提供生命值管理和重生功能。

Features / 功能:

* Restore health for individual or all survivors / 恢复单个或所有生还者的生命值
* Respawn dead players at aim location / 在瞄准位置重生死亡玩家
* Integration with admin menu / 集成到管理员菜单

#### Commands / 命令:

* sm_hp - Restore health for all survivors / 恢复所有生还者生命值
* sm_givehp [player] - Restore health for specific player / 恢复指定玩家生命值
* sm_respawn [player] - Respawn a specific player / 重生指定玩家
