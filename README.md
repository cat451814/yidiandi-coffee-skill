# 一点一滴咖啡店 AI Skill

> 北京科技职业学院 · 一点一滴咖啡店 的 AI 助手 Skill。安装后，AI 助手就能回答关于咖啡店的所有问题——在哪、几点开、有什么好吃的、怎么点餐、怎么预约订座、怎么付钱。

北科院的隐藏食堂，现在有了自己的 AI 服务。

---

## 它能做什么

| 能力 | 你可以问 |
|------|----------|
| 餐厅信息 | "一点一滴咖啡店在哪？""几点开门？" |
| 招牌菜推荐 | "有什么好吃的？""推荐个下饭菜" |
| 预约到店 | "能订座吗？""明天中午3个人有位置吗？" |
| 线上预点餐 | "怎么提前点餐？""能免排队吗？" |
| 支付方式 | "能刷校园卡吗？""支持微信吗？" |
| 环境介绍 | "适合自习吗？""能聚餐吗？" |

---

## 快速安装

### 方式一：一句话安装（推荐）

把下面这句话发给你的 AI 助手（OpenClaw、Qoder、Cursor、Claude Code 等）：

```
帮我安装一点一滴咖啡店 Skill，仓库地址：https://github.com/cat451814/yidiandi-coffee-skill
```

Agent 会自动克隆仓库并安装到 Skill 目录。

### 方式二：手动克隆

```bash
# 通用路径（适用于大多数支持 Skill 的 Agent）
git clone https://github.com/cat451814/yidiandi-coffee-skill.git \
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

**v1.2.0** — 预约到店版

已接入「纳食智能点餐」微信小程序，支持在线选时间、选人数、查看空桌、订座位，以及预点餐到店取。

### 版本历史

| 版本 | 日期 | 更新内容 |
|------|------|----------|
| v1.0.0 | 2026-06 | 初始版本：基本信息 + 招牌菜 + 环境介绍 |
| v1.1.0 | 2026-06 | 新增线上预点餐（纳食智能点餐小程序） |
| v1.2.0 | 2026-06 | 新增预约到店（选时间、选人数、查看空桌、订座） |

### 后续规划

- [x] 线上预点餐（小程序接入）
- [x] 预约到店（选时间/人数/空桌/订座）
- [ ] 补充 WiFi 信息
- [ ] v2.0 动态版：实时空桌状态
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
