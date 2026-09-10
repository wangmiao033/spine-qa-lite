# Spine 动画验收台（精简版 v0.1）

用于游戏换皮和角色 Spine 动画的快速验收。

功能：
- 拖入 `.json/.skel + .atlas + .png`
- 文件仅在浏览器本地读取
- Spine 3.8 / 4.0 / 4.1 / 4.2 Runtime 切换
- 大预览区，默认 135% 放大
- 滚轮缩放、拖动、居中、适配
- 动画列表、播放/暂停、倍速
- 第 0 帧、前后单帧
- 透明棋盘 / 深灰 / 白色 / 创建页模拟背景
- 原静态图覆盖对比
- Bones / Mesh / Bounds Debug
- 一键复制验收报告

部署：整个目录可直接部署到 Vercel、Netlify 或普通静态服务器。

注意：页面使用官方 `@esotericsoftware/spine-player` Runtime。实际内部或外部分发时，请按 Esoteric Software 的 Spine Runtime / Editor 许可执行。
