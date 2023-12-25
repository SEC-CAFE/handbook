---
title: 软件成分分析(SCA)
linkTitle: SCA
weight: 2
description: 软件成分分析与依赖管理工具链
keywords:
 - 软件成分分析
 - SCA
 - Dependency-Check
 - OpenSCA
 - Dependabot
 - Snyk
---

> 开源软件包允许开发人员实现功能，而无需编写所有代码，从而可以加快开发过程。然而，开源代码也带来了开源漏洞。依赖管理工具通过识别和更新带有已知漏洞的包来帮助管理开源包中的漏洞。
<!--more-->

- [OpenSCA](https://opensca.xmirror.cn/) 悬镜开源的SCA工具
- [Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper) 用于kubernetes、虚拟机和无服务器的强大的运行时漏洞扫描器
- [Dependabot](https://dependabot.com/) - 自动扫描GitHub仓库的漏洞，并创建pull请求来合并打过补丁的依赖项
- [Dependency-Check](https://owasp.org/www-project-dependency-check/) - OWASP开源的依赖关系和漏洞扫描工具
- [Dependency-Track](https://dependencytrack.org/) OWASP项目，监控和识别项目中脆弱依赖关系的数量和严重程度
- [JFrog XRay](https://jfrog.com/xray/) JFrog 安全与许可分析工具
- [NPM Audit](https://docs.npmjs.com/cli/audit) NPM CLI内置的node包漏洞审计工具
- [Renovate](https://renovate.whitesourcesoftware.com/) 自动监控和更新多个框架和语言的软件依赖项
- [Requires.io](https://requires.io/) 自动监控Python项目的脆弱依赖关系并进行升级
- [Snyk Open Source](https://snyk.io/) 使用Snyk专用的漏洞数据库自动监控和升级漏洞依赖关系

## 开源工具能力对比

[SecurityTools-Assessment for SCA](https://atomgit.com/cyberchen/SecurityTools-Assessment/tree/master/SCA) 由统信软件、百度、阿里、绿盟共同完成的开源 SCA 工具能力评估报告。

测试结果摘要：

| 工具名称 | 版本 | 得分(第一轮) | 得分(第二轮) | 最终得分 |
| --- | --- | --- | --- | --- |
| OpenSCA | v1.0.12 | 117.61 | 135.61 | 126.61 |
| Murphysec | v3.1.1 | 99.96 | 66.84 | 83.22 |
| DependencyCheck | 8.3.1 | 88.9 | 78.443 | 83.6715 |
| Trivy | 0.42.1 | 76.7 | 86.04 | 81.37 |
| Synk-cli | 1.1196.0 | 72.9 | 53.99 | 63.445 |
