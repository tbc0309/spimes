# spimes 静态字体资源

用于网页部署的字体与图标字体资源集合，可由静态文件服务器直接托管。

## 目录

- `css/Remix/`：Remix Icon 2.5.0 的 CSS、SVG 与 WebFont 文件。
- `fonts/`：`blockdole` 与 `webmo` WebFont 文件。

## 使用

将所需目录部署到站点静态资源路径，并在页面样式中引用对应 CSS 或通过 `@font-face` 加载字体。生产环境建议设置长期缓存，并在替换资源时同步调整缓存版本。

## 许可说明

本仓库聚合的是第三方字体资源，不对全部文件授予统一的开源许可证：

- `css/Remix/` 中的 Remix Icon 2.5.0 保留文件内声明的 Apache License 2.0。
- `fonts/` 中两个字体文件没有随仓库附带可核验的上游许可证，因此不应视为 MIT、Apache 或公有领域资源；公开部署或再分发前，请先确认来源和授权。

详细范围见 [LICENSE.md](LICENSE.md)。
