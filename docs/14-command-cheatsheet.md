# 14 常用命令速查

> 返回：[总目录](index.md)

## 新手与工具

| 命令 | 用途 | 条件 |
| --- | --- | --- |
| `/sfc <物品名>` | 查询 Slimefun 合成材料 | 无 |
| `/sci` | 查看当前区块机器数量和性能影响 | 无 |
| `/playtime` | 查看有效在线时长 | 无 |
| `/playtime <玩家>` | 查看他人有效在线时长 | 无 |

## 经济与交易

| 命令 | 用途 | 条件 |
| --- | --- | --- |
| `/pay <玩家> <金额>` | 玩家转账（3% 税） | Tier 1+，72h 在线 |
| `/nh3export sell <物品ID>` | 出口 Slimefun 工业品换 XP | 按 Tier 限制 |
| `/nh3top wealth` | 查看财富排行 | 需服务器开放 |

### /pay 限制速查

| Tier | 单笔上限 | 每日对同一人上限 |
| --- | --- | --- |
| T0 | 禁止 | — |
| T1 | 50,000 XP | 100,000 XP |
| T2 | 100,000 XP | 100,000 XP |
| T3 | 300,000 XP | 100,000 XP |
| T4 | 1,000,000 XP | 100,000 XP |
| T5 | 无限 | 100,000 XP |

- 最小转账金额：10 XP
- 同一对象冷却时间：60 秒
- 同 IP 转账会被系统拒绝并记录审计日志

## 宏观信息

| 命令 | 用途 | 条件 |
| --- | --- | --- |
| `/nh3macro status` | 查看宏观指标（CPI、Gini） | 需服务器开放 |
| `/nh3stat report` | 经济报告 | 管理员 |

## 领地与记录

| 命令 | 用途 | 条件 |
| --- | --- | --- |
| `/claim` | 圈地 | 无 |
| `/claimslist` | 查看领地列表 | 无 |
| `/trust <玩家>` | 信任玩家进入或使用领地 | 领地内执行 |
| `/co inspect` | CoreProtect 查询模式 | 管理员 |

## 管理员命令

| 命令 | 用途 | 条件 |
| --- | --- | --- |
| `/nh3admin settier <玩家> <Tier>` | 强制设置 Tier | nh3.admin |
| `/nh3admin setpeak <玩家> <XP>` | 强制设置历史峰值 | nh3.admin |
| `/nh3admin event doublexp` | 开启双倍经验活动 | nh3.admin |
| `/nh3admin event stop` | 停止活动 | nh3.admin |
| `/nh3admin policy easing` | 启动宽松政策 | nh3.admin |
| `/nh3admin policy tightening` | 启动紧缩政策 | nh3.admin |
| `/ecoset <物品ID> <倍率>` | 调整发电机倍率 | nh3.admin |
| `/ecocheck` | 查看物品电力倍率 | nh3.admin |