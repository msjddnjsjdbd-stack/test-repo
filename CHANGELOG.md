# CHANGELOG

## 2026-09-26 — Website Execution V1

### 新增
- `AGENTS.md`：Codex / Agent 网站执行规则。
- `data/products.json`：网站商品展示数据单一入口。
- `docs/site-operations.md`：新品上架与发布检查流程。

### 调整
- 根 `README.md` 从测试仓库说明升级为「足球密码 FOOTBALL CODE · 网站执行仓库」。
- `index.html` 从通用 `MY SELECT` 个人展示页升级为足球密码品牌页面。
- 商品列表改为从 `data/products.json` 动态渲染。
- 未提供真实购买链接时，按钮显示“购买链接待接入”。
- 删除页面中未经确认的“高弹、速干、轻量分区”等功能性描述。

### 保持
- 原有三张商品图片继续使用。
- 已确认价格保持为 ¥199 / ¥99 / ¥399。
- 当前仍采用静态 HTML/CSS/JS，不引入大型框架或构建系统。
