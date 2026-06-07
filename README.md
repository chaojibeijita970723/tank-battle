# 🎮 坦克大战 (Tank Battle)

一款纯 HTML/CSS/JavaScript 实现的经典坦克大战网页游戏。

## 🎯 游戏特色

- **经典玩法**：控制你的坦克，消灭所有敌方坦克！
- **多种地图**：每波切换不同的地图（经典十字、要塞、迷宫）
- **波次系统**：每波敌人数量递增，难度逐步提升
- **道具系统**：速度提升、快速射击、护盾、额外生命
- **粒子特效**：爆炸、火花等视觉效果
- **音效系统**：使用 Web Audio API 生成实时音效
- **小地图**：右下角显示战场态势
- **连杀系统**：连续击杀获得额外分数加成

## 🕹 操作说明

| 操作 | 按键 |
|------|------|
| 移动 | `W` `A` `S` `D` 或方向键 |
| 瞄准 | 鼠标移动 |
| 射击 | 鼠标左键 / `空格` / `J` |
| 暂停 | `P` |
| 重新开始 | `R` |

## 🚀 快速开始

1. 克隆仓库：
```bash
git clone https://github.com/chaojibeijita970723/tank-battle.git
```

2. 直接用浏览器打开 `index.html` 即可开始游戏！

或者直接访问 GitHub Pages：`https://chaojibeijita970723.github.io/tank-battle/`


## 🛠 技术栈

- HTML5 Canvas
- CSS3 动画
- Vanilla JavaScript (ES6+)
- Web Audio API

## 📝 游戏规则

- 玩家有 3 条生命，生命耗尽游戏结束
- 消灭当前波次所有敌人进入下一波
- 砖墙可被子弹摧毁，钢铁墙不可摧毁
- 连续击杀可获得分数加成
- 随机掉落道具可提供临时增益

---

Made with ❤️ and JavaScript
