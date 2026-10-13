# WorkTrace 公开下载

其他电脑的 Codex 可以从这里读取任务指令、下载经校验的技能源码，无需 GitHub 登录，也不需要访问私有维护仓库。本仓库仅分发通用代码和说明，不接收公司数据库、员工证据或登录凭据。

## 化工案件员工：独立离线分控

把下面这句话发给目标员工电脑的 Codex，使用 **6.1 Sol / high**：

```text
请读取并完整执行 https://raw.githubusercontent.com/zhoudebao6-art/worktrace-skills-downloads/main/prompts/chemical-offline-collector.txt 。从其中指定的公开 v0.2.1 发布页下载并校验源码，在这台员工电脑完成独立离线分控所需扩展、部署和验收。总控尚未上线，未来也不在同一局域网；数据先在本机保存，数日后生成完整交接包。不要访问私有维护仓库或发起方电脑的本地路径。
```

[阅读完整任务指令](prompts/chemical-offline-collector.txt) · [查看纯文本指令](https://raw.githubusercontent.com/zhoudebao6-art/worktrace-skills-downloads/main/prompts/chemical-offline-collector.txt)

**版本边界：v0.2.1 尚不具备独立离线分控的全部能力。** 这份任务指令要求目标电脑 Codex 实现离线首次建档、本机每日总结、身份接纳与完整移交，完成测试后再部署。它不是声称这些功能已经实现的一键启动命令。现有模式仍要求先由总控登记；单独启用学习执行器不会自动生成分控日任务。

这里的离线指不连接公司总控。模型总结仍需目标电脑自身的有效登录和网络；采集、数据库保存与模型调用的状态分别报告。

## 固定版本源码

打开 [v0.2.1 发布页](https://github.com/zhoudebao6-art/worktrace-skills-downloads/releases/tag/v0.2.1)，下载：

- [worktrace-skills-v0.2.1.zip](https://github.com/zhoudebao6-art/worktrace-skills-downloads/releases/download/v0.2.1/worktrace-skills-v0.2.1.zip)
- [SHA256SUMS.txt](https://github.com/zhoudebao6-art/worktrace-skills-downloads/releases/download/v0.2.1/SHA256SUMS.txt)

请使用这份专用 ZIP，内含 `.worktrace-source.json`；GitHub 自动生成的本下载仓库 Source code ZIP 只有分发说明，不能替代技能源码包。

技能 ZIP：355629 字节，SHA256：

```text
33f7a85212f7f7cfaeac5928c35e949c9100a39cc55b00771947426e1fa372bc
```

先核验哈希，再解压阅读说明。包内原版文档的私有下载入口由本公开入口替代，无须访问私库。不要把本公开下载仓库克隆目录直接当作完整 WorkTrace 技能源目录。

## 源码与维护

源码基线提交：`206a8334755c95fc721f08d9a0ec738c41a4be74`，来源版本 `v0.2.1`。公开下载包与已验证的原版源码包逐字节一致；原维护仓库保持私有，历史提交和账户凭据没有复制到这里。

目标电脑修改源码时保留原包、基础版本及派生修改清单。公司运行数据、交接资料和任何机密材料只保存在公司指定位置，不提交到本仓库、公开 Issue 或 GitHub Release。
