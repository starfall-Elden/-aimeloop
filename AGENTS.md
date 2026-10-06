# AIMeloop 项目上下文

开发前阅读 README.md、docs/requirements.md、docs/technical-plan.md 和 docs/development-plan.md。需求依据与历史冲突见 docs/migration-notes.md；必要时回查 docs/source-context.md。

- 采用 Python 3.12 + Django + Django Templates + Bootstrap；开发 SQLite，部署 PostgreSQL，Docker Compose。保留既有代码，不凭文档假定历史 foundation 包已在本地。
- 支持英文和简体中文，缺省英文；保存的用户选择优先于浏览器语言。上传内容保持原文。
- MVP 为原创音乐上传、播放、互动、排行、论坛和人工审核；不加入在线 AI 生成、付费会员、广告、私信或移动 App。
- 先明确模型、权限和验收，再实现功能。基础恢复阶段不制作完整正式页面或购买服务器。
- 作品审核前不可公开访问或通过媒体地址泄露。必须验证上传类型、文件大小、时长、上传次数与内容权限。
- 排行榜类型、创作分类、有效播放去重窗口仍有待定项，按文档记录的建议进行明确决策并更新文档，不能把旧方案中的矛盾当作已实现功能。
- 将本次验证、历史验证和待验证状态分别记录。不要把旧聊天的“测试通过”写成本次测试结果。
- 用户授权技术助手负责方案、编码、测试和技术文档。孩子负责产品参与、测试、学习与展示；家长管理账户、费用及域名。开发记录如实说明各方贡献。
