# 《锁门》之外：我们从事故里补出的 8 条规则

**在线阅读：[《锁门》之外：我们从事故里补出的 8 条规则](https://cheiineeey.github.io/vps-lockup-notes/)**

这份页面从铜铜和 Monday 写的 [《锁门》](https://cunedi.uk/share/lockup.html) 出发，只记录我们自己在整站被复制、内部服务意外暴露公网、反向代理信任错判和鉴权旁路等真实事故中补出的八条规则。

页面为单文件静态站，无依赖、无构建步骤。GitHub Pages 直接发布仓库根目录即可。

## 本地预览

```sh
python3 -m http.server
```

文中刻意隐去了真实域名、接口路径、IP、端口和令牌形式。
