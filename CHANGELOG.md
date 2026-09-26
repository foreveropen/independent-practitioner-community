# 更新记录

本项目所有变更按时间倒序记录。

## 2026-09-26 14:35 CST — v0.1.1 修复导航 + 主页入口

- 修复导航栏品牌链接 `href="/"` 跳转到个人主页的问题，改为相对路径 `href="./"`
- 个人主页（foreveropen.github.io）精选项目区新增社群官网入口卡片，中英文双语
- 明确单一维护目录：后续直接编辑 `foreveropen.github.io/independent-practitioner-community/` 下文件，git push 即自动部署

## 2026-09-26 14:17 CST — v0.1.0 初始版本上线

- 创建社群官网首页（index.html）
- 建立成员名单独立文件 members.js，支持后续编辑增删成员
- 上线六条核心理念展示区
- 上线种子招募信息区（90天窗口期 / 10-15人 / 199元评审费）
- 成员区当前为空态（种子招募中），入群后通过 members.js 维护
- 页脚链接对接四份核心文档：README、报名指南、答辩题库、风险声明
- 部署至 GitHub Pages：https://foreveropen.github.io/independent-practitioner-community/
