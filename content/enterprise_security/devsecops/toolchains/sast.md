---
title: 静态应用安全测试(SAST)
linkTitle: SAST
weight: 3
description: 静态应用安全测试(SAST)列表
keywords:
 - 静态应用安全测试
 - SAST
 - 代码安全审计
 - 白盒测试
 - CodeQL
 - RIPS
 - SonarQube
---

> 静态应用安全测试(SAST)工具在不执行目标软件的情况下扫描软件中的漏洞。通常，静态分析将扫描源代码以寻找安全缺陷，例如不安全函数的使用、硬编码的秘密和配置问题。SAST工具通常以IDE插件和cli的形式出现，可以集成到CI/CD管道中。
<!--more-->

- [static-analysis](https://github.com/analysis-tools-dev/static-analysis) 静态分析工具清单项目
- [dynamic-analysis](https://github.com/analysis-tools-dev/dynamic-analysis) 动态分析工具清单项目

## 多语言支持
- [DevSkim](https://github.com/microsoft/DevSkim) 微软开源的一组IDE插件、cli和其他工具，可以为许多编程语言提供安全性分析
- [Graudit](https://github.com/wireghoul/graudit/) 自定义或预配置正则表达式签名的潜在安全缺陷的Grep源代码
- [Hawkeye](https://github.com/hawkeyesec/scanner-cli) 模块化的CLI工具，用于项目安全性、脆弱性和一般风险突出
- [LGTM](https://lgtm.com/) 使用自定义或内置CodeQL查询扫描和监控代码的安全漏洞
- [RIPS](https://www.ripstech.com/) 对PHP, Java和Node.js项目进行自动化静态分析
- [SemGrep](https://semgrep.dev/) 一个快速的、开源的静态分析工具，可以在编辑器、提交和CI时发现bug并强制执行代码标准
- [SonarLint](https://www.sonarlint.org/) 一个IDE插件，突出潜在的安全问题、代码质量问题和bug
- [SonarQube](https://www.sonarqube.org/) 扫描代码以解决安全性和质量问题，支持多种语言

## C/C++
- [FlawFinder](https://github.com/david-a-wheeler/flawfinder) 扫描C/C++代码，寻找潜在的安全弱点

## C#
- [Puma Scan](https://github.com/pumasecurity/puma-scan) 一个Visual Studio插件，用于扫描. net项目的潜在安全缺陷


## Java
- [Deep Dive](https://discotek.ca/deepdive.xhtml) JVM部署单元的静态分析，包括Ear, War, Jar和APK
- [Find Security Bugs](https://github.com/find-sec-bugs/find-sec-bugs/) 用于Java web应用程序安全审计的插件。支持Eclipse, IntelliJ, Android Studio和SonarQube
- [SpotBugs](https://github.com/spotbugs/spotbugs) Java应用程序的静态代码分析

## JavaScript
- [ESLint](https://eslint.org/) 具有多种安全检查规则的JavaScript检查工具

## Go
- [Golang Security Checker](https://github.com/securego/gosec) 扫描Go代码潜在安全缺陷的CLI工具

## .NET
- [Security Code Scan](https://github.com/security-code-scan/security-code-scan) C#和VB的静态代码分析


## PHP
- [Phan](https://github.com/phan/phan) 对PHP应用程序进行广泛的静态分析，并支持一些安全扫描特性
- [PHPCS Security Audit](https://github.com/FloeDesignTechnologies/phpcs-security-audit) PHP静态分析，包括PHP、Drupal 7和PHP相关cve的规则
- [Progpilot](https://github.com/designsecurity/progpilot) PHP源代码静态分析


## Python
- [Bandit](https://github.com/PyCQA/bandit) 查找Python代码中常见的安全漏洞


## Ruby
- [Brakeman](https://github.com/presidentbeef/brakeman) 用于检查Ruby on Rails应用程序安全漏洞的静态分析工具
- [DawnScanner](https://github.com/thesp0nge/dawnscanner) Ruby脚本和web应用程序的安全扫描。支持Ruby on Rails, Sinatra和Padrino框架


## 商业软件对比
> 引用自 https://bloodzer0.github.io/ossa/application-security/code-audit/

![](/images/代码审计商业软件对比.png "代码审计商业软件对比")

## 开源工具能力对比

[SecurityTools-Assessment for SAST](https://atomgit.com/cyberchen/SecurityTools-Assessment/tree/master/SAST) 由阿里巴巴、统信软件共同完成的开源 SAST 工具能力评估报告。

### C/C++

| 工具      | 总分  |
| --------- | ----- |
| CodeQL    | 69.88 |
| CppCheck  | 63.57 |
| Infer     | 59.76 |

### Java

| 工具      | 总分  |
| --------- | ----- |
| CodeQL    | 67.42 |
| SpotBugs  | 43.58 |
| Semgrep   | 41.68 |
| Infer     | 36.56 |

