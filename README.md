## 六个网页小游戏使用说明

本项目是纯前端静态页面，无需安装依赖即可运行。

### 文件说明

- `index.html`：游戏导航首页
- `game1-guess-number.html`：猜数字
- `game2-tic-tac-toe.html`：井字棋
- `game3-memory.html`：记忆翻牌
- `game4-2048.html`：2048
- `game5-snake.html`：贪吃蛇
- `game6-reaction.html`：反应速度测试
- `styles.css`：全局样式

### 一、本地使用（Chrome 打开）

你可以用以下任一方式：

#### 方式 A：直接双击打开（最简单）

1. 在 Finder 中进入项目目录。
2. 双击 `index.html`。
3. 如果默认不是 Chrome：右键 `index.html` -> “打开方式” -> 选择 `Google Chrome`。
4. 进入首页后，点击任意游戏即可开始。

#### 方式 B：命令行指定用 Chrome 打开（macOS）

在项目目录执行：

```bash
open -a "Google Chrome" /Users/liujiachi/code/agents/birthGame/index.html
```

如果你想直接打开某个游戏页，也可以把上面的 `index.html` 替换成对应页面，例如：

```bash
open -a "Google Chrome" /Users/liujiachi/code/agents/birthGame/game5-snake.html
```

### 二、通过公网 URL 打开

把项目部署到任意静态托管平台后（如 Vercel、Netlify、GitHub Pages），就可以通过公网链接访问。

假设你部署后的域名是：

`https://your-games.example.com`

那么可分享的 6 个游戏 URL 为：

- `https://your-games.example.com/game1-guess-number.html`
- `https://your-games.example.com/game2-tic-tac-toe.html`
- `https://your-games.example.com/game3-memory.html`
- `https://your-games.example.com/game4-2048.html`
- `https://your-games.example.com/game5-snake.html`
- `https://your-games.example.com/game6-reaction.html`

首页导航地址：

- `https://your-games.example.com/index.html`

### 三、给朋友分享建议

- 想让朋友自己选游戏：分享 `index.html` 地址。
- 想直接让朋友进入某一款：分享对应游戏页面 URL。
- 手机也可访问（页面已做基础自适应）。
