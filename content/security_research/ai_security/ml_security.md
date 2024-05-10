---
title: 机器学习(ML)安全
prev: /security_research/ai_security/llm_security/
weight: 3
description: 机器学习(ML)安全相关资料
keywords:
 - Machine Learning Security
 - ML Security
 - 机器学习安全
---


## 指南
- [Machine Learning Security Top 10 (2023 edition)](https://mltop10.info/)

##  Machine Learning Security Top 10 详情(机器翻译)
- **ML01:2023 Input Manipulation Attack 输入操纵攻击** 输入操纵攻击是一个总称，它包括对抗性攻击，即攻击者故意改变输入数据以误导模型的一种攻击。。
- **ML02:2023 Data Poisoning Attack 数据投毒攻击**  数据投毒攻击是指攻击者操纵训练数据，导致模型的行为不符合预期。。
- **ML03:2023 Model Inversion Attack 模型逆向攻击**  当攻击者对模型进行逆向工程以从中提取信息时，就会发生模型逆向攻击。
- **ML04:2023 Membership Inference Attack 成员推断攻击**  当攻击者操纵模型的训练数据以使其行为暴露敏感信息时，就会发生成员推断攻击。。
- **ML05:2023 Model Theft 模型窃取** 当攻击者获得模型参数的访问权时，就会发生模型窃取攻击。
- **ML06:2023 AI Supply Chain Attacks AI供应链攻击**  当攻击者修改或替换系统使用的机器学习库或模型时，就会发生AI供应链攻击。这也可以包括与机器学习模型相关的数据。
- **ML07:2023 Transfer Learning Attack 移学习攻击**  当攻击者在一项任务上训练模型，然后在另一项任务上微调模型，使其表现得不符合预期时，就会发生迁移学习攻击。
- **ML08:2023 Model Skewing 模型倾斜**  模型偏斜攻击是指攻击者操纵训练数据的分布，使模型以不期望的方式运行。
- **ML09:2023 Output Integrity Attack 输出完整性攻击**  在输出完整性攻击场景中，攻击者的目的是修改或操纵机器学习模型的输出，以改变其行为或对使用它的系统造成伤害。
- **ML10:2023 Model Poisoning 模型投毒**  模型投毒攻击发生在攻击者操纵模型的参数，使其以不期望的方式行为时。


## 攻击
- [针对机器学习模型的变音符号文本对抗攻击](https://www.freebuf.com/vuls/383999.html)
- [欺骗机器的艺术：对抗性攻击的原理与方法](https://mp.weixin.qq.com/s/zdDo4evMofXlyOiRk_AgSw)

## 工具
- [Adversarial Robustness Toolbox](https://adversarial-robustness-toolbox.readthedocs.io/en/latest/) 一个用于机器学习防御对抗性威胁的 Python 库
- [Privacy Meter](https://github.com/privacytrustlab/ml_privacy_meter) 一个用于审查机器学习模型数据隐私情况的 Python 库
- [Audit AI](https://pypi.org/project/audit-AI/) 美国公司 pymetrics 开发的用于机器学习偏差测试的 Python 库