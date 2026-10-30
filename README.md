# ArcheCausal-Skills

文档职责：维护项目组共享的 Codex skills 及其专用参考资料。

适用范围：项目组内部 skill 的开发、验证与分发；应用源码仍保存在各自的项目仓库。

## 目录约定

共享 skill 放在 `.agents/skills/<skill-name>/`，每个 skill 自带 `SKILL.md` 和它实际需要的 references、scripts 或 agents 元数据。

## 使用方式

在 Codex 中打开本仓库可以维护和验证其中的项目级 skills。需要在其他项目中调用时，将对应 skill 安装到个人 Codex skills 目录，或使用团队统一的 skill 安装方式。SSH 私钥、密码和服务令牌由每位成员本地管理，不提交到本仓库。

## 分支约定

先在 `test` 分支验证 skill 变更；团队确认后再合并到 `main`。
