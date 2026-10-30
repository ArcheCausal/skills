# ArcheCausal-Skills Agent Rules

文档职责：规定项目组共享 Codex skills 的调用边界与敏感信息处理规则。

适用范围：本仓库全部内容。

- 用户提供 `release.zip` 并要求部署或回滚 CausalAgent 腾讯云测试/预发环境时，必须调用 `tencent-cloud-release-deploy` skill。
- 每位成员使用自己的 SSH 私钥；私钥、密码、令牌和服务器环境密钥不进入本仓库。
