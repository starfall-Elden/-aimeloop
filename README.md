# AIMeloop

原创音乐与 AI 音乐社区，面向人工原创、AI 辅助和 AI 生成作品，提供上传、播放、排行与论坛。名称暂定，项目用于学生兴趣探索和大学申请展示，目标是低成本、非商业 MVP。

本目录于 2026-10-05 从应用可读取的 AiMusic 相关聊天整理建立。当前交付是项目上下文与开发文档，不是已迁移的运行代码或完整云端项目。

## 项目文档

- [需求与验收标准](docs/requirements.md)
- [技术方案与数据设计](docs/technical-plan.md)
- [开发计划与当前状态](docs/development-plan.md)
- [来源、决策差异与迁移范围](docs/migration-notes.md)
- [可读取的原始聊天文字](docs/source-context.md)

GitHub 远端：https://github.com/starfall-Elden/-aimeloop （仓库名开头包含连字符）。本地已初始化 main 分支并配置 origin。2026-10-05 查询远端未返回分支或提交；本地文档尚未提交或推送。

原始聊天归档 docs/source-context.md 保留本地并由 .gitignore 排除；整理后的需求、技术方案和开发计划可纳入版本管理。

下一步从基础代码恢复与验证开始。先检查历史 foundation 包或远端仓库，验证 Django 骨架和语言机制，再按开发计划实施用户系统及上传审核。
