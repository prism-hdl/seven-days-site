# 七日创造 · 站点产物

这是 [prism-hdl/seven-days](https://github.com/prism-hdl/seven-days) 的**构建产物**仓库，用于 GitHub Pages 托管，内容请勿直接编辑。

- 正文源码：私有仓库 `prism-hdl/seven-days` 的 `episodes/`
- 生成方式：`node scripts/fetch-fonts.mjs`（自托管的裁剪字体）→ `node scripts/build-site.mjs`（带侧边栏目录的 `web/`）→ 整份拷进本仓库；发布前用 `node scripts/check-site.mjs` 在 390×844 逐页体检
- 线上地址：https://prism-hdl.github.io/seven-days-site/

`.nojekyll` 用于跳过 Jekyll 构建，让 HTML 原样发布。
