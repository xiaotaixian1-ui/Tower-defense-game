# Tower-defense-game

萤火峡谷 · 塔防 - 一款基于 HTML5 的网页塔防游戏

## 🎮 游戏简介

这是一款以萤火虫为主题的塔防游戏，玩家需要在峡谷中布置防御塔，阻止敌人通过。游戏采用现代 HTML5 技术构建，支持响应式设计和移动端触控操作。

## 📁 项目结构

```
.
├── src/                    # 重构后的源代码目录
│   ├── index.html         # 主 HTML 文件
│   ├── css/
│   │   └── styles.css     # 样式表
│   ├── js/
│   │   └── game.js        # 游戏逻辑
│   └── data/              # 数据文件（预留）
├── v1.0.html              # 初始版本（存档）
├── v1.7.html              # 功能增强版（存档）
├── v2.0 beta.html         # 测试版本（存档）
└── v2.3.html              # 最新单体版本（存档）
```

## 🚀 快速开始

### 方式一：直接打开重构版本

```bash
# 推荐打开重构后的版本
open src/index.html          # macOS
xdg-open src/index.html      # Linux
start src/index.html         # Windows
```

### 方式二：使用本地服务器

```bash
cd src
python3 -m http.server 8080
# 然后访问 http://localhost:8080/
```

### 方式三：打开历史版本

```bash
# 推荐打开最新版本
open v2.3.html          # macOS
xdg-open v2.3.html      # Linux
start v2.3.html         # Windows
```

## 🎯 游戏特性

- 🌟 **精美画面** - 渐变背景、粒子效果、流畅动画
- 📱 **响应式设计** - 支持桌面端和移动端
- 🏹 **策略塔防** - 合理布置防御塔抵御敌人
- 💰 **经济系统** - 击杀敌人获得金币
- ❤️ **生命系统** - 防止敌人突破防线
- ⏸️ **暂停功能** - 随时暂停/继续游戏

## 🎨 技术栈

- HTML5 Canvas
- CSS3 (变量、动画、渐变)
- Vanilla JavaScript
- Google Fonts (Noto Sans SC, ZCOOL KuaiLe)

## 📝 操作说明

- **放置防御塔** - 点击或拖拽到地图上
- **查看状态** - 顶部显示金币和生命值
- **暂停/继续** - 使用控制按钮

## 📄 重构说明

本项目已从单体 HTML 文件重构为模块化结构：

### 重构内容

1. **HTML/CSS/JS 分离** - 将原 `v2.3.html` 中的样式提取到 `css/styles.css`，脚本提取到 `js/game.js`
2. **目录结构优化** - 创建清晰的 `src/` 目录结构，便于维护和扩展
3. **保留历史版本** - 所有原始版本文件保持不变，作为开发历史记录

### 优势

- ✅ 代码更清晰易读
- ✅ 便于版本控制和协作开发
- ✅ 样式和逻辑分离，易于维护
- ✅ 支持浏览器缓存，提升加载性能

---

*享受你的塔防之旅！* 🦋