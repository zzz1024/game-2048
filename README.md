# 2048 网页版

这是一个基于 HTML, CSS 和 JavaScript 实现的经典 2048 游戏。

## 🎮 如何玩
1.  **PC 端**：使用键盘方向键 (⬆️⬇️⬅️➡️) 或 WASD 键移动方块。
2.  **移动端**：在屏幕上滑动手指来移动方块。
3.  **目标**：合并相同的数字，直到拼出 **2048**！

## 🚀 部署到 GitHub Pages

1.  在 GitHub 上创建一个新的仓库（例如命名为 `game-2048`）。
2.  将本地代码推送到远程仓库：
    ```bash
    git remote add origin https://github.com/<你的用户名>/game-2048.git
    git branch -M main
    git push -u origin main
    ```
3.  进入仓库的 **Settings** -> **Pages**。
4.  在 **Build and deployment** 下，选择 **Source** 为 `Deploy from a branch`。
5.  在 **Branch** 选项中，选择 `main` 分支并点击 **Save**。
6.  等待几分钟，刷新页面，你将获得一个公网访问地址，例如：`https://<你的用户名>.github.io/game-2048/`。

## 🛠️ 本地运行
直接用浏览器打开 `index.html`，或者使用本地服务器：
```bash
python3 -m http.server 8000
```
然后访问 `http://localhost:8000`。
