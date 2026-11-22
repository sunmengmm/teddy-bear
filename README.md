# 毛绒小熊

[在线玩《毛绒小熊》](https://sunmengmm.github.io/teddy-bear/)

一个可以用鼠标互动的 3D 毛绒玩具小游戏。可以按住肚子、顺毛摸、点前爪招手，也可以抓住前爪、耳朵或脚掌拎起来。拖动空白处可以转动视角。

## 打开游戏

用支持 WebGPU 的新版 Chrome 或 Edge 打开 `index.html`。这个 HTML 已包含小熊模型、绒毛和交互，可以离线运行。

## 发布到 GitHub Pages

将仓库的 `main` 分支推送到 GitHub，在仓库的 Settings → Pages 选择 `Deploy from a branch`，将发布源设为 `main` 分支的 `/(root)` 并保存。[GitHub Pages 官方说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch)

`blender/` 存放制作文件，`references/` 存放参考资料，`web/` 是原在线版的源码仓库。Git 忽略这些目录和离线副本 `毛绒小熊.html`。GitHub Pages 使用 `index.html`。
