# kuailu-geo-prompt-map

快鹭 GEO 提示词图谱公开展示页，仓库描述为 54 条提示词。

## 内容与本地预览

默认分支只有 `index.html` 1 个普通文件。

这是静态发布仓。在仓库根目录运行 `python3 -m http.server 8080 --bind 127.0.0.1`，访问 `http://127.0.0.1:8080/`。

<!-- repository-maintenance:begin -->
## 维护与发布

本仓独立维护；与其他业务系统之间通过已公开的 API 或固定版本包协作。运行配置与业务数据不纳入源码维护快照。

公开入口：https://yuruizhang688-cloud.github.io/kuailu-geo-prompt-map/ 。Pages 源目录为 `main/`。

日常变更先在分支提交，通过本仓验证后使用 Pull Request 合入 main。仓库保护以 GitHub 实际设置为准；个人私有仓的保护规则可能受套餐限制。Issue 用于记录缺陷与待办，缺少 Issue 不代表没有工作。

维护快照使用 `maintenance-YYYYMMDD.N` 标签与 GitHub Release 记录源码版本；它不自动代表生产部署、真实平台验收或桌面安装包发布。Tag 发布后保持不可变，修正使用新版本。

许可范围见根目录 LICENSE；第三方代码、字体和素材保留各自许可证。不要提交 .env、Cookie、访问令牌、浏览器资料或运行数据库。
<!-- repository-maintenance:end -->
