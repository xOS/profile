# Home

零框架、零外部依赖的个人主页。页面样式与 SVG 图标库都内置在 `index.html` 中，页面内容仅请求一张 WebP 头像，站点图标使用独立的 `favicon.svg`。

## 使用内置图标

在链接中加入下面的结构即可复用图标，不会产生额外的网络请求：

```html
<svg class="icon" aria-hidden="true">
  <use href="#icon-github" />
</svg>
```

目前共预置 70 个图标：

- 页面现用：`arrow-up-right`、`blog`、`mail`、`location`、`server`、`status`、`stripe`、`ifdian`
- 通用导航：`home`、`user`、`link`、`globe`、`search`、`menu`、`plus`、`check`、`info`、`external-link`、`chevron-right`、`copy`、`download`、`upload`、`sun`、`moon`
- 内容沟通：`rss`、`book`、`bookmark`、`file`、`folder`、`tag`、`calendar`、`clock`、`bell`、`message`、`send`
- 开发设施：`code`、`terminal`、`database`、`cloud`、`wifi`、`cpu`、`shield`、`lock`、`key`、`monitor`、`package`
- 媒体内容：`camera`、`image`、`video`、`play`、`music`、`headphones`
- 支付支持：`heart`、`coffee`、`gift`、`card`、`wallet`、`kofi`、`ifdian`
- 社交平台：`instagram`、`telegram`、`github`、`x`、`youtube`、`linkedin`、`discord`、`weibo`、`bilibili`、`zhihu`、`facebook`、`tiktok`

调用时统一在名称前添加 `icon-`，例如 `youtube` 对应 `#icon-youtube`。
