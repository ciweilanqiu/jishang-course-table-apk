# 吉商课程表 APK 分发

本仓库只存放可公开分发的 APK，供 jsDelivr 做 CDN 源（大陆访问速度明显优于 Cloudflare Pages 直连）。

- 每版一个 tag，例如 1.4.1-code8
- CDN 地址：`https://cdn.jsdelivr.net/gh/ciweilanqiu/jishang-course-table-apk@<tag>/<file>`
- 完整性以 update.json 里的 sha256 为准；本仓库不含源码
