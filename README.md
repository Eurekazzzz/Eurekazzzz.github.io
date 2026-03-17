# 🏠 Eurekazzzz.github.io

> 私人工具站 —— 小黑屋

个人 GitHub Pages 站点，收录了一些有趣的小工具和网页小游戏。

🔗 **在线访问：** [https://eurekazzzz.github.io](https://eurekazzzz.github.io)

---

## 📦 站点内容

| 工具 | 路径 | 说明 |
|------|------|------|
| 🏠 首页 | `/` | iOS 风格的工具导航页，毛玻璃效果 |
| 📧 小说阅读器 | `/Gmail/` | Gmail 风格伪装界面，适合偷偷看小说 |
| 💎 宝石消除 | `/Gem/` | 经典 8×8 三消小游戏，带交换动画和粒子爆炸特效 |

## 🎮 更多游戏

以下游戏也托管在 GitHub Pages 上，独立仓库：

- [🐍 贪吃蛇](https://eurekazzzz.github.io/snake-game/) — 赛博朋克霓虹风格
- [🔫 战术行动](https://eurekazzzz.github.io/shooter-game/) — Three.js 3D FPS
- [💎 宝石战争](https://eurekazzzz.github.io/match3-game/) — 像素风三消 RPG

## 🛠️ 技术栈

- 纯 HTML5 + CSS3 + Vanilla JavaScript
- 零依赖，浏览器直接打开即可运行
- iOS 风格 UI（毛玻璃、圆角卡片、响应式布局）
- Canvas 2D 动画 & Web Audio API

## 📂 项目结构

```
├── index.html          # 首页导航
├── Gem/
│   └── index.html      # 宝石消除游戏
├── Gmail/
│   └── index.html      # 小说阅读器（Gmail 伪装）
└── pictures/           # 宝石素材图片
    ├── BLUE.png
    ├── GOLD.png
    ├── GREEN.png
    ├── PINK.png
    ├── ROSE.png
    ├── SILVER.png
    └── SKYBLUE.png
```

## 🚀 本地运行

```bash
# 使用 Python
python -m http.server 8080

# 使用 Node.js
npx serve .
```

然后访问 `http://localhost:8080`

---

© 2026 Eurekazzzz
