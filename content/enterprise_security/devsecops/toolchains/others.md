---
title: 其他工具
linkTitle: Others
weight: 7
description: DevSecOps工具链中其他安全工具
keywords:
 - 其他安全工具
 - 安全靶场
 - 凭据管理工具
 - 敏感凭据扫描工具
---


## 靶场

- [Bad SSL](https://github.com/chromium/badssl.com) 一个运行大量SSL / TLS配置不佳的web服务器的容器。对于测试工具很有用
- [Cfngoat](https://github.com/bridgecrewio/cfngoat) 用于在AWS中创建有意不安全的服务堆栈的云形成模板。非常适合作为上述代码分析工具测试云形成基础设施
- [Damn Vulnerable Web App](http://www.dvwa.co.uk/) 一个提供安全环境来理解和利用常见Web漏洞的Web应用程序
- [Juice Shop](https://github.com/bkimminich/juice-shop) 一个包含OWASP十大安全漏洞的web应用程序
- [NodeGoat](https://github.com/OWASP/NodeGoat) 一个Node.js web应用程序，它演示并提供了解决常见安全漏洞的方法
- [Terragoat](https://github.com/bridgecrewio/terragoat) 用于在AWS、Azure和GCP中创建有意不安全的服务堆栈的Terraform模板。非常适合作为上述代码分析工具测试Terraform基础架构
- [Vulnerable Web Apps Directory](https://owasp.org/www-project-vulnerable-web-applications-directory) 一个用于学习的有漏洞的Web应用程序的集合

## 风险与应急响应管理
- [SRCMS](https://github.com/martinzhou2015/SRCMS) 企业应急响应与缺陷管理系统
- [洞察](https://github.com/creditease-sec/insight2) 宜信安全开源的集应用系统资产管理、漏洞全生命周期管理、安全知识库管理三位一体的平台
- [DefectDojo](https://github.com/DefectDojo/django-DefectDojo) 一个DevSecOps, ASPM(应用程序安全状态管理)和漏洞管理工具
- [W5 SOAR](https://github.com/w5teams/w5) 安全编排与自动化响应平台
- [Faraday](https://github.com/infobyte/faraday) 用于安全编排、漏洞管理和集中信息的安全套件
- [Camunda](https://github.com/camunda/camunda-bpm-platform) 工作流和过程自动化
- [StackStorm](https://github.com/StackStorm/st2) 支持事件驱动安全性的跨服务和工具的集成和自动化平台

## 凭据管理

> 我们编写的软件需要使用机密信息(密码、API密钥、证书、数据库连接字符串)来访问资源，但我们不能将机密信息存储在代码库中，因为这会使它们容易受到攻击。秘密管理工具提供了一种安全存储、访问和管理秘密的手段。

- [AWS Key Management Service (KMS)](https://aws.amazon.com/kms/) AWS密钥管理服务(KMS)
- [Google Cloud Key Management Service (KMS)](https://cloud.google.com/kms) 谷歌云密钥管理服务(KMS)
- [Azure Key Vault](https://azure.microsoft.com/en-au/services/key-vault/) Azure密钥管理服务(KMS)

- [Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html) 将机密信息安全地存储在Ansible管道中
- [AWS Secrets Manager](https://aws.amazon.com/secrets-manager/) 在AWS中安全存储可检索的应用程序机密信息
- [BlackBox](https://github.com/StackExchange/blackbox) 加密代码仓库中的凭证
- [Chef Vault](https://github.com/chef/chef-vault) 安全地将秘密存储在Chef中
- [CredStash](https://github.com/fugue/credstash) 使用KMS和DynamoDB在AWS中安全地存储密钥
- [CyberArk Application Access Manager](https://www.cyberark.com/products/privileged-account-security-solution/application-access-manager/) 应用程序的秘密管理，包括秘密轮换和审计
- [Docker Secrets](https://docs.docker.com/engine/swarm/secrets/) 在Docker集群中存储和管理对Secrets的访问
- [Gopass](https://github.com/gopasspw/gopass) 依赖Git和gpg的团队的密码管理器。管理加密文件和存储库中的机密
- [HashiCorp Vault](https://www.vaultproject.io/) 通过UI、CLI或HTTP API安全地存储密钥
- [Keyscope](https://github.com/SpectralOps/keyscope) 一个Rust内置的开源密钥和秘密工作流工具(验证，失效等)
- [Pinterest Knox](https://github.com/pinterest/knox) 安全存储、轮换和审计机密信息
- [Secrets Operations (SOPS)](https://github.com/mozilla/sops) Mozilla开源工具，加密存储在YAML、JSON、ENV、INI和二进制文件中的密钥
- [Teller](https://github.com/spectralops/teller) 一个开发人员的秘密管理工具


## 敏感凭据扫描

- [CredScan](https://secdevtools.azurewebsites.net/helpcredscan.html) Azure提供的一个可以作为任务在Azure DevOps管道中运行的凭据扫描工具
- [Detect Secrets](https://github.com/Yelp/detect-secrets) 检测和防止代码中凭据
- [GitGuardian](https://www.gitguardian.com/) 一个基于web的解决方案，它可以扫描和监控公共和私有git存储库中的机密信息
- [Gitleaks](https://github.com/zricethezav/gitleaks) 一个SAST工具，用于检测硬编码的秘密，如密码、api密钥和令牌等git仓库中的秘密
- [Nightfall](https://nightfall.ai/solutions/product/github) 一个基于web的平台，用于监控跨多个SDLC工具(包括GitHub仓库)的敏感数据泄露
- [Repo-supervisor](https://github.com/auth0/repo-supervisor) 密钥扫描工具，可以以CLI、Docker容器或AWS Lambda运行
- [SpectralOps](https://spectralops.io) - _Spectral_ - 自动化代码安全、机密、令牌和敏感数据扫描工具
- [truffleHog](https://github.com/trufflesecurity/truffleHog) git仓库凭据搜索工具，可深入挖掘提交历史和分支
- [Git Secrets](https://github.com/awslabs/git-secrets) 扫描Git仓库，寻找代码中提交的秘密或提交消息

## 其他

- [Csper](https://csper.io/report-uri) 一组内容安全策略工具，可以测试策略、监视CSP报告并提供指标和警报

