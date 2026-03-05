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

### 四、GitHub Pages 部署（获得公网地址）

下面按步骤操作，一次部署后即可长期通过公网 URL 访问。

#### 1）把项目推送到 GitHub 仓库

如果你还没初始化或还没提交，可在项目目录执行：

```bash
git init
git add .
git commit -m "init: six web mini games"
```

然后把本地仓库关联到你的 GitHub 仓库并推送（把下面仓库地址替换成你自己的）：

```bash
git branch -M main
git remote add origin https://github.com/<你的用户名>/<你的仓库名>.git
git push -u origin main
```

如果你之前已配置过 `origin`，提示重复，可先执行：

```bash
git remote -v
```

若地址不对再改：

```bash
git remote set-url origin https://github.com/<你的用户名>/<你的仓库名>.git
git push -u origin main
```

#### 2）在 GitHub 开启 Pages

1. 打开你的仓库页面。
2. 进入 `Settings` -> `Pages`。
3. 在 `Build and deployment` 下：
   - `Source` 选择 `Deploy from a branch`
   - `Branch` 选择 `main`
   - 文件夹选择 `/ (root)`
4. 点击 `Save`。

通常等待几十秒到几分钟后，GitHub 会显示站点地址。

#### 3）你的公网地址格式

部署成功后，默认访问地址通常是：

`https://<你的用户名>.github.io/<你的仓库名>/`

对应 6 个游戏可直接分享：

- `https://<你的用户名>.github.io/<你的仓库名>/game1-guess-number.html`
- `https://<你的用户名>.github.io/<你的仓库名>/game2-tic-tac-toe.html`
- `https://<你的用户名>.github.io/<你的仓库名>/game3-memory.html`
- `https://<你的用户名>.github.io/<你的仓库名>/game4-2048.html`
- `https://<你的用户名>.github.io/<你的仓库名>/game5-snake.html`
- `https://<你的用户名>.github.io/<你的仓库名>/game6-reaction.html`

首页导航地址：

- `https://<你的用户名>.github.io/<你的仓库名>/index.html`

#### 4）后续更新发布

以后你只要修改页面并再次推送，GitHub Pages 会自动更新：

```bash
git add .
git commit -m "feat: update game pages"
git push
```

#### 5）常见问题

- 页面 404：确认仓库名、用户名、URL 路径大小写完全一致。
- 刚部署打不开：通常是还在发布，等 1~3 分钟后刷新。
- 样式丢失：确认 `styles.css` 已提交且页面中引用路径正确。



https://liujiachi1997.github.io/birthGame/game1-guess-number.html

https://liujiachi1997.github.io/birthGame/game2-tic-tac-toe.html

https://liujiachi1997.github.io/birthGame/game3-memory.html

https://liujiachi1997.github.io/birthGame/game4-2048.html

https://liujiachi1997.github.io/birthGame/game5-snake.html

https://liujiachi1997.github.io/birthGame/game6-reaction.html

https://liujiachi1997.github.io/birthGame/index.html