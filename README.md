# 👊 暴打老板

一款零依赖、可离线游玩的中文点击放置游戏。疯狂点击老板、积累金币、升级装备，并挑战不断强化的 Boss。

## 在线游玩

[在线游玩：beat-the-boss-game.pages.dev](https://beat-the-boss-game.pages.dev/)

## 本地运行

直接用浏览器打开 `index.html` 即可，无需安装依赖或启动服务。

## 玩法

- 点击老板造成伤害并获得金币；购买装备提升点击伤害、每秒伤害和暴击率。
- 每 5 关为限时狂暴关；卡关时可退回已解锁关卡刷金币。
- 进度保存在浏览器的 `localStorage`，每 5 秒自动存档。

## 部署

这是静态站点。Cloudflare Pages 的构建设置应为：

- Framework preset：`None`
- Build command：留空
- Build output directory：`/`

如需把项目放在仓库子目录中，请将根目录设置为该子目录，或把 `index.html` 移到仓库根目录。

## 技术

原生 HTML、CSS、JavaScript；音效由 Web Audio API 实时生成，不依赖任何第三方资源。

## 免责声明

本游戏纯属娱乐，请勿模仿。现实中的职场问题建议通过合法、理性的方式解决。
