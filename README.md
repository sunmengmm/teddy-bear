# 毛绒小熊

一个可以按肚子、顺毛摸、牵爪和拎起来的 3D 毛绒玩具小游戏。

[在线体验](https://sunmengmm.github.io/teddy-bear/) · [GitHub 仓库](https://github.com/sunmengmm/teddy-bear)

## 操作

点击前爪招手，拖动前爪、耳朵或脚掌拎起小熊；拖动空白处旋转视角，点击“重置”恢复初始状态。

## 本地运行

需要 Python 3 和支持 WebGPU 的浏览器，无需安装依赖。在项目目录运行：

```sh
python3 -m http.server 5173 --bind 127.0.0.1
```

访问 <http://127.0.0.1:5173>，按 `Ctrl+C` 停止服务。

## 文件

`index.html` 包含完整游戏。`blender/`、`references/`、`web/` 和离线副本 `毛绒小熊.html` 仅保存在本地，已被 Git 忽略。

## 发布

GitHub Pages 使用 `main` 分支的 `/(root)` 目录。修改后提交并推送到 GitHub，网站会自动更新；仅保存本地文件不会更新网站。
