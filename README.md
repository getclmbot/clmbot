# getclmbot community

这是 clmbot 的公开社区支持仓库，用于承载使用问答、问题反馈、功能与适配建议、部署经验和社区规范。

## 关于 clmbot

clmbot 是由 **SslTrus Inc.** 提供并维护的证书交付与自动部署工具：

- 安装包对非商业用途免费；
- 个人和组织可用于学习、研究、评估与内部测试；企业生产环境、客户交付和其他商业用途需要另行书面授权；
- 允许以非商业目的复制、镜像或再分发未经修改的官方安装包；
- 可连接 CaaS，也可持续适配私有 CLM 或其他证书服务；
- 支持将证书部署到客户管理的服务器、中间件、Kubernetes Secret 和普通证书目录；
- 程序与 clmbot.org 网站源代码当前均不公开；
- 项目计划未来开源，但尚未公布时间或许可证。

本仓库不包含 clmbot 产品源代码，也不是网站源码仓库。

## clmbot 与 CaaS

CaaS 是证书生命周期管理服务。CaaS 可以通过厂商 API 直接部署到 CDN、WAF、负载均衡等云产品，也可以使用 clmbot 将证书部署到客户管理的服务器和私有环境。

**clmbot 是 CaaS 的一种部署方式，不代表 CaaS 的全部能力。**

## 使用入口

- 官网：https://www.clmbot.org/zh/
- 下载：https://www.clmbot.org/zh/download/
- 文档：https://www.clmbot.org/zh/docs/
- GitHub Discussions：https://github.com/orgs/getclmbot/discussions
- Issues：https://github.com/getclmbot/clmbot/issues
- 安全报告：security@clmbot.org

使用问题请进入 Discussions 的 **Q&A**；开放建议和适配需求请进入 **Ideas**；能够稳定复现的缺陷请提交 Issue。

## 安全提醒

公开内容不得包含 AccessKey、AccessSecret、私钥、证书内容、客户域名、内网地址或未经脱敏的日志。未修复的安全漏洞必须通过私密安全渠道报告。

社区交流须遵守 [Code of Conduct](CODE_OF_CONDUCT.md) 和 [参与说明](CONTRIBUTING.md)。

二进制软件的允许用途、再分发要求、禁止事项与无保证条款见 [clmbot 二进制软件非商业使用许可](BINARY_LICENSE.md)。
