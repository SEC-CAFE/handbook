---
title: 标准与指南
weight: 1
description: LLM安全标准与指南
keywords:
 - AI Security Standards
 - AI Security Guide
 - LLM Security Guide
 - AI Security and Privacy Guide
---

## 标准规范与白皮书
- [生成式人工智能服务安全基本要求](https://www.tc260.org.cn/upload/2024-03-01/1709282398070082466.pdf)
- [生成式人工智能治理与实践白皮书](https://max.book118.com/html/2023/1217/6114033151010022.shtm)

## 指南

###  OWASP Top 10 for Large Language Model Applications
- [项目地址](https://owasp.org/www-project-top-10-for-large-language-model-applications/)
- [中文版翻译](https://github.com/OWASP/www-project-top-10-for-large-language-model-applications/blob/main/assets/translations/zh/OWASP%20%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E5%BA%94%E7%94%A8Top%2010%20%E5%AE%89%E5%85%A8%E5%A8%81%E8%83%81.pdf)
- [解读及攻击举例](https://blog.csdn.net/stingfire/article/details/136688741)

- **LLM1：提示词(Prompt) 注入(Injection)** 黑客通过设计过的输入（提示词）操纵大型语言模型
(LLM)，从而导致 LLM 执行意外操作。提示词注入会覆盖系统提示词，而间接注入操纵外部数据源进
行注入攻击。
- **LLM2 不安全的输出处理**  当 LLM 输出未经审查而被接受时，就会出现此漏洞，从而暴露后端系统。
滥用可能会导致 XSS、CSRF、SSRF、权限升级或远程代码执行等严重后果。
- **LLM3 训练数据中毒**  当 LLM 培训数据被篡改，引入损害安全性、有效性或道德行为的漏洞或偏见
时，就会发生这种情况。来源包括 Common Crawl、 WebText 、 OpenWebText和书籍。
- **LLM4 拒绝服务模型**  攻击者对大型语言模型进行资源密集型操作，导致服务降级或高成本。由于
LLM的资源密集型性质和用户输入的不可预测性，该漏洞被放大。
- **LLM5 供应链漏洞**  LLM 应用程序生命周期可能会受到易受攻击的组件或服务的影响，从而导致安全
攻击。使用第三方数据集、预先训练的模型和插件可能会增加漏洞。
- **LLM6 敏感信息披露**  LLM可能会在其回复中泄露机密数据，从而导致未经授权的数据访问、隐私侵
犯和安全漏洞。实施数据清理和严格的用户策略来缓解这种情况至关重要。
- **LLM7 不安全的插件设计**  LLM 插件可能具有不安全的输入和不足的访问控制。缺乏应用程序控制使
它们更容易被利用，并可能导致远程代码执行等后果。
- **LLM8 过度代理**  基于LLM的系统可能会采取导致意想不到的后果的行动。该问题源于授予基于 LLM
的系统过多的功能、权限或自主权。
- **LLM9 过度依赖**  过度依赖LLM而不受监督的系统或人员可能会因LLM生成的不正确或不适当的内容而
面临错误信息、沟通不畅、法律问题和安全漏洞。
- **LLM10 模型盗窃**  这涉及对专有LLM模型的未经授权的访问、复制或泄露。影响包括经济损失、竞争
优势受损以及敏感信息的潜在访问。

[LLM应用安全开发实践](https://blog.csdn.net/stingfire/article/details/136918878)
补充解读与建议的安全策略

![](/images/owasp_llm_app_security.png "LLM应用安全开发实践")

> 从上图中可以看出：
> 
> 针对LLM输入，可能存在漏洞：提示注入 / 模型拒绝服务。<br>
> 针对LLM输出，可能存在漏洞：敏感信息泄漏 / 不安全的输出处理 / 过度依赖。<br>
> 针对训练数据 / 微调数据的输入，可能存在漏洞：训练数据毒化 / 敏感信息泄漏。<br>
> 针对用户输入 / 模型 / 训练数据，可能存在漏洞： 模型盗窃。<br>
> 针对插件，可能存在漏洞：过度代理 / 不安全的插件设计。<br>
> 针对下游服务，可能存在漏洞：过度代理 / 供应链漏洞。


### [OWASP]LLM AI Cybersecurity &Governance Checklist
- [英文原版PDF](https://owasp.org/www-project-top-10-for-large-language-model-applications/llm-top-10-governance-doc/LLM_AI_Security_and_Governance_Checklist-v1.1.pdf)
- [中文版](https://blog.csdn.net/manok/article/details/136169690)

###  [Lakera]Comprehensive Guide to Large Language Model (LLM) Security
大型语言模型(LLM)安全综合指南
- [简介](https://www.lakera.ai/blog/llm-security#deployment-strategies-and-best-practices)
- [完整PDF](https://lakera-marketing-public.s3.eu-west-1.amazonaws.com/Lakera_AI_LLM+Security+Playbook_v2_.pdf)
- [PDF备份地址](https://sec.cafe/handbook/pdf/Lakera_AI_LLM+Security+Playbook_v2_.pdf)

###  [Bright]Exploring the Security Risks of Using Large Language Models
探索使用大型语言模型的安全风险
- [介绍文章](https://brightsec.com/whitepapers/exploring-the-security-risks-of-using-large-language-models/)
- [PDF版本](https://brightsec.com/wp-content/uploads/2023/11/Exploring-the-Risks-of-Using-Large-Language-Models-Final.pdf)
- [PDF备份地址](https://sec.cafe/handbook/pdf/Exploring-the-Risks-of-Using-Large-Language-Models-Final)


###  [Secop Solution]A Comprehensive Guide to LLM Security and Governance 
LLM安全和治理的全面指南
- [介绍文章](https://www.secopsolution.com/blog/llm-security-and-governance)

