# kyfd

我是刘丰熙。秋招主要投 Go 后端，平台和 DevOps 也可以看。

我写东西比较较真。规则过没过、SQL 有没有真的跑过、通行证能不能用第二次，这些我想能在代码和测试里对上，而不是只在文档里写「支持」。

## 最近在做的

**[ChangeGuard](https://github.com/kyfd/changeguard)** 是我花时间最多的项目。生产变更先检查、再审批，然后给 CI 发一张一次性通行证。通行证绑的是文件 SHA-256，批完再改文件就会被拦住。它不连生产库，也不接管 Git 或 Kubernetes。

[v3.0.1](https://github.com/kyfd/changeguard/releases/tag/v3.0.1) 已经发在默认分支上。

![ChangeGuard 变更单](https://raw.githubusercontent.com/kyfd/changeguard/main/docs/assets/01-change-list.webp)

**[栖境](https://github.com/kyfd/qijing)** 是我在 Windows 上给自己用的文件观察工具。默认不联网，只看你授权过的目录，默认只读元数据。真要清理，也只是移进回收站，还得逐项点确认。有未签名的 [Windows 包](https://github.com/kyfd/qijing/releases/tag/v0.1.0)，SmartScreen 可能会拦一下。

水下鱼群计数的训练代码在 **[DVSD-Net](https://github.com/kyfd/DVSD-Net)**。投算法岗再翻这个，投后端可以略过。

## 技术

日常是 Go、PostgreSQL、Redis、Docker、Kubernetes、GitHub Actions。Windows 客户端用过 Wails，前端会一点 Vue，研究代码是 Python。

邮箱：1027864314@qq.com
