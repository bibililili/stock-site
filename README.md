# stock-site

A股与美股主要股指盘后追踪，部署在 https://stock.asymptos.com 。

- `index.html`：页面本体。每日数据写在页面里的 `<script id="market-data">` 数据块中，定时任务只替换这一段。
- `CNAME`：GitHub Pages 自定义域名。

数据整理自公开财经资讯，仅作个人研究记录，不构成投资建议。
