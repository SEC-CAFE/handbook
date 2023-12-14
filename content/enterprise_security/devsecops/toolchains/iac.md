---
title: 基础设施即代码(IaC)
linkTitle: IaC
weight: 6
description: 基础设施即代码(IaC)，容器、K8S、运维工具等配置安全检查工具列表
keywords:
 - 基础设施即代码
 - IaC
 - 容器安全扫描
 - 容器安全基线
 - Terraform 配置安全
 - Ansible 配置安全
---

> 基础设施即代码允许将应用程序可靠地部署到一致的环境中。这不仅确保了基础设施得到一致的加固，而且提供了一个静态和动态分析基础设施定义的机会，这些定义涉及易受攻击的依赖项、硬编码的秘密、不安全的配置和安全配置中的意外更改。下面的工具有助于这种分析。
<!--more-->

## 容器及K8S
- [Anchore Engine](https://anchore.com/opensource/) 深入检查cve的Docker镜像并检查自定义策略。引擎支持与注册表、协调器和CI/CD产品集成的企业产品
- [Clair](https://github.com/quay/clair) 扫描应用程序容器和Docker容器以查找公开披露的漏洞
- [Dagda](https://github.com/eliasgranderubio/dagda/) 将Docker容器中安装的操作系统和软件依赖版本与公开的漏洞数据库进行比较，并执行病毒扫描
- [Docker-Bench-Security](https://github.com/docker/docker-bench-security) Docker Bench for Security是一个脚本，它可以检查在生产环境中部署Docker容器的几十种常见最佳实践
- [Hadolint](https://github.com/hadolint/hadolint) 检查Dockerfile中已知的规则，并在RUN语句中验证内联bash代码
- [Snyk Container](https://snyk.io/product/container-vulnerability-management/) 在CI/CD期间或通过持续监控扫描Docker和Kubernetes应用程序的安全漏洞
- [Trivy](https://github.com/aquasecurity/trivy) 简单而全面的容器漏洞扫描器
- [Kube-Score](https://github.com/zegl/kube-score) 扫描Kubernetes对象定义以查看安全性和性能配置错误
- [Kubectrl Kubesec](https://github.com/controlplaneio/kubectl-kubesec) kubesec.io插件，可以对Kubernetes资源进行安全风险分析

## 其他
- [Cfn Nag](https://github.com/stelligent/cfn_nag) 扫描AWS CloudFormation模板以查看不安全配置
- [Checkov](https://github.com/bridgecrewio/checkov) 扫描Terraform、AWS CloudFormation和Kubernetes模板以进行不安全配置
- [KICS](https://github.com/Checkmarx/kics) 在开发周期的早期发现安全漏洞、合规问题和基础设施错误配置
- [Spectral DeepConfig](https://spectralops.io/blog/spectral-launches-deepconfig-to-ensure-no-misconfiguration-at-all-layers-of-software/) 在提交时发现基础设施和应用程序中的错误配置
- [Terrascan](https://github.com/accurics/terrascan) 在配置云原生基础设施之前，将基础设施作为代码检测合规和违反安全的情况，以降低风险
- [Regula](https://github.com/fugue/regula) 在部署之前评估Terraform基础设施作为代码的潜在安全错误配置和违反规定的情况
- [Terraform Compliance](https://terraform-compliance.com/) 一个针对Terraform的轻量级、安全和合规性测试框架，为您的基础架构即代码启用负面测试功能
- [Tfsec](https://github.com/liamg/tfsec) 扫描Terraform模板，查看安全配置错误和不符合AWS、Azure和GCP安全最佳实践
- [Ansible-Lint](https://github.com/ansible-community/ansible-lint) 检查playbook中可能需要改进的实践和行为
- [Conftest](https://github.com/instrumenta/conftest) 创建自定义测试来扫描配置文件中的安全缺陷
- [cfsec](https://github.com/aquasecurity/cfsec) 对CloudFormation模板进行静态分析，以识别常见的错误配置
 

