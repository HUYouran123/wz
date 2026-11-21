# :octocat: wz

> 这是一个 HUYouran 的网站

![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-live-2f5d8a?logo=github&logoColor=white)
![Static](https://img.shields.io/badge/site-static%20HTML-orange?logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-not%20set-lightgrey)

[:wave: 在线访问](https://huyouran123.github.io/wz/) · [:memo: 源码](https://github.com/HUYouran123/wz) · [:books: 个人主页 README](https://github.com/HUYouran123/HUYouran123)

把 GitHub 个人主页那段介绍，做成了一个能直接打开的网页。

---

## :wave: 这是什么

纯静态单页，只有 HTML 和 CSS。无 JS、无框架、无构建步骤、无外部依赖，深浅色跟随系统。

不是博客，不是项目文档，也不是下面几个站的官网。就是一张放大的个人卡片：我是谁、平时在维护什么、去哪找源码。

内容和 [`HUYouran123/HUYouran123`](https://github.com/HUYouran123/HUYouran123) 个人主页的 README 是同一套。那边用 Markdown 写在仓库首页，这边是网页，两边按同一口径改就行，不用互相复制页面。

## :card_index_dividers: 这张卡片上有什么

线上页一共五块，顺序和这里一致：

- **我是谁** — 站是自己搭的，更新不快，但一直在；不是官方，不运营被收录的服务器
- **在维护的站** — 导航 / 收录 / 资料，三个站各一张小卡
- **GitHub** — 说明这一页和个人主页 README 的关系，挂两个仓库链接
- **标签** — 技术栈与范围，纯展示
- **几句说明** — 收录不代表推荐、在线数据只是探测那一刻、非官方声明

增删区块直接改 `index.html` 里对应的 `<section>`，样式在 `style.css`，不用动别的文件。

## :globe_with_meridians: 在维护的站

| | 站点 | 说明 |
| :--- | :--- | :--- |
| 导航 | [mcpenav.top](https://mcpenav.top/) | 最早的 MCPE 0.14 综合导航，服务器入口、客户端下载。Cloudflare Pages 托管，更新较慢 |
| 收录 | [mc.mcpenav.top](https://mc.mcpenav.top/) | MCPEMAP 服务器收录站，0.13～1.1，人工审核、免费收录。列表与在线数据以这里为准 |
| 资料 | [pm.mcpenav.top](https://pm.mcpenav.top/) | 0.14 便携版核心站，版本协议矩阵、核心对照、配置与排错。开服包不预置演示条目 |

页面文案以 `index.html` 为准

## :label: 标签

`Minecraft PE` · `MCPE 0.14` · `PHP` · `静态站点` · `Cloudflare Pages` · `服务器收录` · `开源维护` · `版本协议矩阵`

标签是范围说明，不是技能认证。要加就往 `index.html` 的 `.tags` 里塞一个 `<span>`，样式会自动排。
