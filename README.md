# 物品清单 PWA

记录、管理、分类我拥有的东西。本地优先（IndexedDB），无后端，可安装到手机主屏幕离线使用。

## 部署（GitHub Pages）

1. 在 GitHub 新建仓库（例如 `item-keeper`）。
2. 把本目录所有文件上传到仓库主分支根目录。
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，分支选主分支、目录选 `/ (root)`，Save。
4. 等 1-2 分钟，访问 `https://你的用户名.github.io/item-keeper/`。
5. 在安卓 Chrome 打开该地址 → 右上 ⋮ → 安装应用 / 添加到主屏幕。

## 文件说明

- `index.html` — 应用主体（含全部样式与脚本）
- `manifest.json` — PWA 清单
- `sw.js` — Service Worker（离线缓存）
- `icon-192.png` / `icon-512.png` / `icon-maskable-512.png` — 应用图标
- `apple-touch-icon.png` — iOS 主屏幕图标
- `favicon-32.png` — 浏览器标签图标
