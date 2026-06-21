# 🐾 宠物小精灵世界之旅：新的大陆

<div align="center">

**Pokémon World Journey: The New Continent**

*A Pokémon fan-made RPG — embark on an adventure across Kanto and beyond*

[![Engine](https://img.shields.io/badge/Engine-RPG%20Maker%20XP%201.05-blue)](https://www.rpgmakerweb.com/)
[![Runtime](https://img.shields.io/badge/Runtime-RGSS104E-red)](https://www.rpgmakerweb.com/)
[![Language](https://img.shields.io/badge/Script-Ruby%20(RGSS)-cc342d)](https://www.ruby-lang.org/)
[![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc/4.0/)
[![Status](https://img.shields.io/badge/Status-Chapter%203%20Complete-brightgreen)]()

</div>

---

## 📖 目录 | Table of Contents

- [简介 | Introduction](#-简介--introduction)
- [游戏截图 | Screenshots](#-游戏截图--screenshots)
- [游戏特色 | Features](#-游戏特色--features)
- [安装运行 | Installation](#-安装运行--installation)
- [操作指南 | Controls](#-操作指南--controls)
- [游戏系统 | Game Systems](#-游戏系统--game-systems)
  - [属性与数值 | Stats & Attributes](#属性与数值--stats--attributes)
  - [进化机制 | Evolution](#进化机制--evolution)
  - [经验分配 | Experience Distribution](#经验分配--experience-distribution)
  - [属性克制 | Type Matchups](#属性克制--type-matchups)
- [地图与地区 | Maps & Regions](#-地图与地区--maps--regions)
- [攻略提示 | Tips & Hints](#-攻略提示--tips--hints)
- [项目结构 | Project Structure](#-项目结构--project-structure)
- [制作团队 | Credits](#-制作团队--credits)
- [许可证 | License](#-许可证--license)
- [免责声明 | Disclaimer](#-免责声明--disclaimer)

---

## 🎮 简介 | Introduction

**宠物小精灵世界之旅：新的大陆**是一款基于 **RPG Maker XP** 开发的宝可梦（Pokémon）同人角色扮演游戏。

### 故事背景

主人公是一位在平原中被救起的失忆少年。身份不明、过往成谜的他，从大木博士手中获得了第一只精灵，从此踏上了"精灵战争"的擂台。没有束缚、没有指引，他在这片大陆上独自前行。然而，随着冒险的深入，与身世相关的命运正悄然接近——这究竟是寻回记忆的旅途，还是……

> *A young amnesiac trainer, rescued from the wilderness with no memory of his past, receives his first Pokémon from Professor Oak. With no one to guide him and nothing to hold him back, he steps onto the stage of Pokémon battles. But as he journeys deeper, destiny creeps closer — is this truly a quest to recover lost memories, or something far greater?*

### 地区设定

游戏包含两个主要地区：
- 🗾 **关东地区 (Kanto)** — 经典城镇与道馆，从真新镇出发，穿越常磐森林、月见山，挑战八大道馆
- ☁️ **天空大陆 (Sky Continent)** — 全新的冒险区域，更多的精灵与挑战

---

## 📸 游戏截图 | Screenshots

> *截图即将更新，敬请期待 | Screenshots coming soon*

| 标题画面 | 城镇探索 | 精灵对战 |
|:---:|:---:|:---:|
| ![Title](Graphics/Titles/) | ![Town](Graphics/) | ![Battle](Graphics/Battlebacks/) |

---

## ✨ 游戏特色 | Features

- 🐣 **247+ 种精灵** — 收录关东地区及更多精灵，每种精灵都有独特的数值与技能
- 🗺️ **354 张地图** — 庞大的游戏世界，涵盖城镇、洞窟、森林、海域、道馆等多样化场景
- ⚔️ **精灵战争系统** — 回合制对战，支持属性克制、会心一击、状态异常等丰富机制
- 📈 **自由加点成长** — 每升一级获得属性点，进化后重新分配，打造专属精灵
- 🔄 **可控进化** — 精灵达到进化等级后由玩家决定是否进化，战略性十足
- 🎵 **丰富视听体验** — 200+ 首背景音乐、280+ 种音效、数百张战斗精灵图
- 🏆 **30层战斗塔** — 挑战极限，赢取觉醒水晶、稀有技能、树果等丰厚奖励
- 🎨 **精灵命名换色** — 自定义精灵名称颜色，打造个性化队伍
- 🌐 **联网对战（试验性）** — 通过 NetGame.dll 支持联网功能
- 📖 **属性克制系统** — 18种属性，物理/特殊攻击分离，策略深度十足

---

## 💿 安装运行 | Installation

### 系统要求

| 项目 | 最低配置 | 推荐配置 |
|------|----------|----------|
| 操作系统 | Windows XP / Vista / 7 / 10 / 11 | Windows 10 / 11 |
| 内存 | 32 MB | 256 MB+ |
| 显卡 | 任意支持 DirectX 的显卡 | — |
| 存储空间 | 约 500 MB | — |

### 运行方法

1. **下载本仓库**
   ```bash
   git clone https://github.com/你的用户名/仓库名.git
   ```
   或直接下载 ZIP 压缩包并解压。

2. **运行游戏**
   双击 `Game.exe` 即可启动游戏。

> ⚠️ **注意**：游戏依赖 `RGSS104E.dll` 运行时库，请确保该文件与 `Game.exe` 在同一目录下。如遇到运行问题，尝试安装 [RPG Maker XP RTP](https://www.rpgmakerweb.com/run-time-package)。

---

## 🎮 操作指南 | Controls

| 按键 | 功能 |
|:---:|------|
| `↑ ↓ ← →` | 移动角色 |
| `空格` / `C` / `Enter` | 确认 / 调查 / 对话 |
| `X` / `Esc` | 取消 / 打开菜单 |
| `X` + `C` (重复) | 快速跳过对话 |
| 按住确认键 | 跑步 |
| `Q` | 骑乘自行车 |
| `Z` / `Shift` | 打开小地图 |
| `F12` | 重置游戏 |

---

## 📐 游戏系统 | Game Systems

### 属性与数值 | Stats & Attributes

每升一级获得 **1点属性点**，进化后可以重新分配所有点数。

```
力量 (ATK)    — 影响攻击与技能的威力
普防 (DEF)    — 降低普通攻击与普攻技能的伤害
特防 (S.DEF)  — 降低特攻技能的伤害
普攻 (P.ATK)  — 影响攻击与普攻技能的威力
特攻 (S.ATK)  — 影响特攻技能的威力
灵巧 (DEX)    — 影响攻击与会心一击率
速度 (SPD)    — 影响逃跑、回避、攻击顺序、速度技能威力
HP            — 生存体力
PP            — 发动技能消耗的点数
```

**加点效率：**
| 属性点 | 提升效果 |
|:---:|------|
| 1点普攻 | +0.25 力量 |
| 1点特攻 | +0.25 力量 |
| 1点灵巧 | +1.0 普防 |
| 1点PP | +0.1 特防 |
| 1点速度 | +0.05 回避 |

### 进化机制 | Evolution

- 达到进化等级后，在物品栏中使用宠物即可进化
- **不进化的优势**：学习技能速度更快
- **进化的优势**：能力值大幅提升，更加"强壮"
- 进化后等级不变，但技能会有变动
- ⚠️ **进化前请卸下所有装备**，进化后装备会消失！

### 经验分配 | Experience Distribution

- 经验由**出战精灵平均分配**
- 队伍人数越多，每只精灵获得的经验越少
- **死亡（濒死）的精灵不会获得经验**
- 全部精灵死亡 → 0 经验

```
对战经验 = 100 × (敌人等级 - 1)
比试金钱 = 敌人总等级 × 10 + 特殊奖励
```

### 属性克制 | Type Matchups

| 分类 | 属性 |
|------|------|
| **普攻类 (Physical)** | 格斗 · 毒 · 地面 · 飞行 · 虫 · 岩石 · 龙 · 恶 · 钢 |
| **特攻类 (Special)** | 火 · 水 · 电 · 草 · 冰 · 超能 · 幽灵 |

---

## 🗺️ 地图与地区 | Maps & Regions

### 关东地区城镇

| 城镇 | 特色 |
|------|------|
| 🌿 真新镇 | 故事开始的地方 |
| 🌲 常磐市 | 常磐森林入口 |
| ⛰️ 尼比市 | 岩石系道馆 |
| 💧 华蓝市 | 水系道馆 |
| ⚡ 枯叶市 | 电系道馆 |
| 👻 紫苑镇 | 精灵塔 |
| 🌈 彩虹市 | 彩虹游戏中心 |
| 🧬 金黄市 | 希鲁夫公司总部 |
| 🥷 浅红市 | 毒系道馆 |
| 🌋 红莲镇 | 红莲研究所 |

### 特殊区域

月见山 · 华蓝洞 · 地鼠山洞 · 石英高原 · 精灵塔 · 狩猎区 · 冠军之路 · 无人发电厂 · 双子岛 · 常磐森林

---

## 💡 攻略提示 | Tips & Hints

### 捕捉精灵

- 使用道具"精灵球"进行捕捉
- 只能捕捉**等级为 1**的精灵
- 每种精灵仅可捕捉**一次**

### 30层战斗塔奖励（随机获得）

| 序号 | 奖励 |
|:---:|------|
| 1 | 🧊 觉醒水晶（随机其一） |
| 2 | 📜 技能（随机 1~19 号技能） |
| 3 | 🍒 树果（随机一种） |
| 4 | ⭐ 双倍经验卡 ×1 |
| 5 | 🍀 四叶草 ×1 |

### 特训手册（部分）

| 精灵 | 特训效果 |
|------|------|
| 皮卡丘 #025 | 速度+50, 灵巧+50, 特防+50, 普攻+50, 特攻+100, 回避+40 |
| 铁甲暴龙 #112 | 速度+50, 特攻+50, 特防+50 |
| 百变怪 #132 | 全能力+100 |
| 卡比兽 #143 | 速度+100 |
| 哈克龙 #148 | 全能力+80, 回避+20 |

### 精灵命名换色

在名字后面加 `,` 再加数字即可改变显示颜色：

| 数字 | 颜色 | 示例 |
|:---:|------|------|
| 0 | 🟠 橙 | `小智,0` |
| 1 | 🔵 深蓝 | `小智,1` |
| 2 | 🔴 红 | `小智,2` |
| 3 | 🟢 绿 | `小智,3` |
| 4 | 🔵 蓝 | `小智,4` |
| 5 | 🟣 紫 | `小智,5` |
| 6 | 🟡 黄 | `小智,6` |
| 7 | 🟤 棕 | `小智,7` |

---

## 📁 项目结构 | Project Structure

```
宠物小精灵世界之旅/
├── Game.exe                  # 游戏启动程序
├── Game.ini                  # 游戏配置文件（指定RGSS库）
├── Game.rxproj               # RPG Maker XP 项目文件
│
├── Data/                     # 游戏数据（Ruby Marshal 格式 .rxdata）
│   ├── Scripts.rxdata        # ★ 所有游戏脚本（Ruby RGSS）
│   ├── Actors.rxdata         # 角色数据
│   ├── Classes.rxdata        # 职业/精灵种类数据
│   ├── Skills.rxdata         # 技能数据
│   ├── Items.rxdata          # 道具数据
│   ├── Enemies.rxdata        # 野生精灵数据
│   ├── Map001~354.rxdata     # ★ 354张地图数据
│   └── ...                   # 更多数据文件
│
├── Graphics/                 # 游戏图形资源
│   ├── Battlers/             # ★ 战斗精灵图（数百张）
│   ├── Characters/           # ★ 地图行走图
│   ├── Icons/                # 道具/精灵图标
│   ├── Pictures/             # ★ 精灵大图鉴（001-247号）
│   ├── Tilesets/             # 地图图块素材（20+套）
│   └── ...                   # 更多图形资源
│
├── Audio/                    # 音频资源
│   ├── BGM/                  # ★ 背景音乐（~200首）
│   ├── BGS/                  # 背景环境音
│   ├── ME/                   # 效果短曲
│   └── SE/                   # ★ 音效（~280个）
│
├── 游戏地图(不完全)/          # 参考地图
│   ├── 关东地区地图.png
│   └── 天空大陆地图.png
│
├── 宠物小精灵游戏介绍.txt     # 原始游戏说明文档
├── 克制表.PNG                # 属性克制关系图
├── Save1.rxdata              # 存档文件
│
└── DLLs/                     # 运行时库
    ├── RGSS104E.dll          # RGSS 运行时
    ├── NetGame.dll           # 网络功能
    └── screenshot.dll        # 截图功能
```

---

## 👥 制作团队 | Credits

### 初代制作 | Original Development (2007)

| 角色 | 成员 |
|------|------|
| 🎯 **主工程** | **Jhhuang.King (J)** |
| 📊 数据整理 | Jq.K |
| 📖 精灵图鉴策划 | 千唏 |

**特别呜谢 | Special Thanks:**

rubygomax · 柳柳 · 索尔迦·蓝 · 精灵使者 · K' · 孤独de思念 · cftx
以及所有 66RPG 社区的支持者和宝可梦爱好者

### 续作开发 | Continued Development

| 角色 | 成员 |
|------|------|
| 🎯 **续作作者** | **秋刀鱼** [Telegram: @Q1udaoyu] |

---

## 📜 许可证 | License

本游戏采用 [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) 许可协议。

- ✅ **可自由分享** — 在任何媒介以任何形式复制、发行本作品
- ✅ **可自由修改** — 修改、转换或以本作品为基础进行创作
- ⚠️ **需署名** — 必须给出适当的署名，提供指向本许可协议的链接
- ❌ **禁止商用** — 不得将本作品用于商业目的

> 游戏制作日期：**2007年08月01日**
>
> 游戏禁止用于商业用途，否则责任将由玩家个人或团体承担。

---

## ⚠️ 免责声明 | Disclaimer

- 本项目为宝可梦（Pokémon/Pocket Monsters）**同人粉丝作品**，与 Nintendo、Game Freak、Creatures Inc. 及 The Pokémon Company **无关**。
- 游戏中的精灵形象、名称、设定等**版权归原版权方所有**。
- 本项目为**非商业性质**的同人创作，仅用于学习交流与怀旧分享。
- 如涉及版权问题，请联系作者进行处理。

---

<div align="center">

**🐾 Gotta Catch 'Em All! 踏上属于你的精灵冒险之旅吧！ 🐾**

⭐ 如果喜欢这个项目，请点亮 Star 支持我们！ ⭐

</div>
