# chrismas-tree-v17.6

单文件圣诞树 Web 作品（Canvas 2D，无第三方依赖）。

- 拖拽旋转 / 滚轮缩放
- 点击树触发灯光波浪
- 许愿：输入一句话，光球升上树梢（本地 localStorage 保存）
- 音效开关（WebAudio 合成，默认开，可关）
- 存图：导出 PNG
- 支持 reduced-motion 静态降级

## 本地打开

直接双击 `index.html`，或：

```powershell
start index.html
```

## 发布到 GitHub Pages

1. 在 GitHub 新建仓库 `chrismas-tree-v17.6`（Public）。
2. 在本目录执行：

```powershell
git remote add origin https://github.com/<你的用户名>/chrismas-tree-v17.6.git
git push -u origin main
```

3. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，分支 `main`、目录 `/ (root)`，保存。
4. 等 1 分钟左右，访问 `https://<你的用户名>.github.io/chrismas-tree-v17.6/`。

`.nojekyll` 已包含，避免 GitHub 用 Jekyll 处理。
