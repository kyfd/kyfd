# Hi, I'm kyfd

**Go Backend / Platform Engineering / DevSecOps**

我关注可靠性、安全边界和工程可验证性：规则检查要能复现，审批后的制品要能绑定，通行证只能用一次，审计链要能离线核对。

## 求职方向

- 主投：Go 后端、基础架构 / 平台工程、DevOps / DevSecOps / 云原生
- 次选：Windows 客户端、全栈
- 算法 / 计算机视觉岗才会把 DVSD-Net 放到第一位

## 熟悉技术栈

Go · PostgreSQL · Redis · Docker · Kubernetes · GitHub Actions · Windows / Wails · 少量 Vue / Python

## 代表项目

| 项目 | 一句话 | 适合讲什么 |
| --- | --- | --- |
| [ChangeGuard](https://github.com/kyfd/changeguard) | 生产变更门禁：检查 SQL / 配置 / Kubernetes，审批后签发一次性通行证 | 一致性、安全边界、发布治理 |
| [栖境](https://github.com/kyfd/qijing) | Windows 本地优先、隐私友好的文件观察工具 | 路径安全、最小权限、本地产品工程 |
| [DVSD-Net](https://github.com/kyfd/DVSD-Net) | 水下鱼群密度估计研究实现 | 仅算法岗 |

投后端 / 平台岗时请从 ChangeGuard 看起。

### ChangeGuard 在解决什么

```text
Developer / Git Repository
          |
          v
    Change Submission
          |
          v
  Normalize + Redact + Hash
          |
     +----+----+
     |         |
 Static Rules  PostgreSQL Shadow Validation
     |         |
     +----+----+
          |
       Review
          |
       Approval
          |
 One-time Passport
          |
    CI Verify / Consume
          |
       Deployment
```

三个值得继续问的问题：

1. 如何防止审批后文件被修改？
2. 如何防止通行证重放或重复使用？
3. 如何证明 SQL 和回滚实际被验证过？

答案在仓库的 README、[威胁模型](https://github.com/kyfd/changeguard/blob/main/docs/threat-model.md) 和测试里，不在口头承诺里。

## 联系

- GitHub：[@kyfd](https://github.com/kyfd)
- Email：1027864314@qq.com
