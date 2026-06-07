---
AIGC:
    Label: "1"
    ContentProducer: 001191440300708461136T1XGW3
    ProduceID: 86db5a914a5bc328d46f09cc12b033b3_727792ad622c11f18f065254007bceed
    ReservedCode1: cApqpNdXF1id8NFx7UQCRLKNB2LfjNawNBvbf50Qi1/JIX+CJQtpAmnJ4QOZG2SE+DWDQdrgDzbq7Jj5mLmMtxvSH9EDG7NPTre43jc3Sga24xxQyJEB75Uz5u4ZAeSdItU6RYzuuj/Hw0eGV0xjrwEJS+ii7sGtKkSfweooGt8eL+zKdJT3jnitecs=
    ContentPropagator: 001191440300708461136T1XGW3
    PropagateID: 86db5a914a5bc328d46f09cc12b033b3_727792ad622c11f18f065254007bceed
    ReservedCode2: cApqpNdXF1id8NFx7UQCRLKNB2LfjNawNBvbf50Qi1/JIX+CJQtpAmnJ4QOZG2SE+DWDQdrgDzbq7Jj5mLmMtxvSH9EDG7NPTre43jc3Sga24xxQyJEB75Uz5u4ZAeSdItU6RYzuuj/Hw0eGV0xjrwEJS+ii7sGtKkSfweooGt8eL+zKdJT3jnitecs=
---

# 一点一滴咖啡店 AI Skill

> 北京科技职业学院 · 一点一滴咖啡店 的 AI 助手 Skill。安装后，AI 助手就能回答关于咖啡店的所有问题——在哪、几点开、有什么好吃的、怎么付钱。

北科院的隐藏食堂，现在有了自己的 AI 服务。

---

## 它能做什么

| 能力 | 你可以问 |
|------|----------|
| 餐厅信息 | "一点一滴咖啡店在哪？""几点开门？" |
| 招牌菜推荐 | "有什么好吃的？""推荐个下饭菜" |
| 支付方式 | "能刷校园卡吗？""支持微信吗？" |
| 环境介绍 | "适合自习吗？""能聚餐吗？" |

---

## 快速安装

### 方式一：一句话安装（推荐）

把下面这句话发给你的 AI 助手（OpenClaw、Qoder、Cursor、Claude Code 等）：

```
帮我安装一点一滴咖啡店 Skill，仓库地址：https://github.com/你的用户名/yidiandi-coffee-skill
```

Agent 会自动克隆仓库并安装到 Skill 目录。

### 方式二：手动克隆

```bash
# 通用路径（适用于大多数支持 Skill 的 Agent）
git clone https://github.com/你的用户名/yidiandi-coffee-skill.git \
  .agents/skills/yidiandi-coffee-skill
```

不同 IDE/客户端的 Skill 目录：

| IDE / 客户端 | Skill 目录 |
|-------------|-----------|
| Qoder | `.qoder/skills/yidiandi-coffee-skill/` |
| Cursor | `.cursor/skills/yidiandi-coffee-skill/` |
| Claude Code | `.claude/skills/yidiandi-coffee-skill/` |
| Windsurf | `.windsurf/skills/yidiandi-coffee-skill/` |
| 通用 | `.agents/skills/yidiandi-coffee-skill/` |

只要目录下有 `SKILL.md`，Agent 下次启动就会自动加载。

---

## 项目结构

```
yidiandi-coffee-skill/
├── SKILL.md          # 核心文件：元数据 + 餐厅信息 + AI 指令
├── README.md         # 项目说明与安装指南
└── LICENSE           # MIT 开源协议
```

---

## 当前版本

**v1.0.0** — 静态版

信息由店主手动维护。更新菜单、营业时间等需要修改 `SKILL.md` 并重新推送仓库。

### 后续规划

- [ ] 补充 WiFi 信息
- [ ] v2.0 动态版：接入实时排队取号
- [ ] v2.0 动态版：在线预点餐到店取
- [ ] v2.0 动态版：每日特价菜自动更新

---

## 信息维护

如果你是一点一滴咖啡店的运营者，需要更新信息：

1. 编辑 `SKILL.md` 中对应的内容
2. 提交并推送到仓库
3. 用户重新加载 Skill 后即可获取最新信息

---

## 灵感来源

本项目受 [金谷园饺子馆 AI Skill](https://github.com/JinGuYuan/jinguyuan-dumpling-skill) 启发，按照相同的 Skill 架构为校园餐厅打造专属 AI 助手。

---

## 协议

[MIT](LICENSE) © 2026 一点一滴咖啡店
*（内容由AI生成，仅供参考）*
