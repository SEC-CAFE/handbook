---
title: 安全工具
weight: 4
description: 区块链/Web3安全工具
keywords:
 - smart contract security
 - 智能合约安全
 - Token 安全
 - DeFi 安全
 - Web3安全工具
---

> 内容主要来自 [Web3-Security-Tools](https://github.com/Quillhash/Web3-Security-Tools)，做部分补充

## 总览
![](/images/Web3_Security_Tools.png "区块链/Web3安全工具")

## VM相关
- [ZIION VM](https://www.ziion.org/)

## 区块链取证工具

### 区块链浏览器

- [Etherscan](https://etherscan.io/)
- [btc.com](https://btc.com/)
- [Bscscan](https://bscscan.com/)
- [Polygonscan](https://polygonscan.com/)
- *通用浏览器*
    1. [Blockchain.com](https://www.blockchain.com/explorer)
    2. [Blockchair.com](https://blockchair.com/)

### 智能合约反编译

- [Dedaub](https://library.dedaub.com/decompile)
- [Panoramix](https://github.com/palkeo/panoramix)
- [abi-decompiler](https://github.com/Decurity/abi-decompiler)
- [Eveem](http://www.eveem.org/) Solidity反编译器


### 浏览器插件

- [Tenderly](https://chrome.google.com/webstore/detail/tenderly-debugger/miiolgcpknpjjfagkaddfgakbdenenfn)
- [MetaDock](https://chrome.google.com/webstore/detail/metadock/fkhgpeojcbhimodmppkbbliepkpcgcoo)
- [Sentio](https://chromewebstore.google.com/detail/sentio/kkdofmcnddcnldoingfpiojnnkdcbhnf)
- [Blockchair](https://chrome.google.com/webstore/detail/blockchair/fhhkkooikehnkaodebbfnkinedlllcfk)
- [Impersonator](https://chrome.google.com/webstore/detail/impersonator/hgihfkmoibhccfdohjdbklmmcknjjmgl)

### Rug 检查工具

- [Rug Pull Finder](https://www.rugpullfinder.io/confirmedrugpulls)
- [bscheck](http://bscheck.eu/)
- [rugscreen](http://rugscreen.com/)
- [QuillCheck](https://quillaudits.com/tools/quillcheck/)
- [poocoin’s rugcheck](https://poocoin.app/rugcheck)
- [tokensniffer](https://tokensniffer.com/)
- [rugpulldetector](http://rugpulldetector.com/)
- [rugdoc honeypot checker](https://rugdoc.io/honeypot/)

### Txn 可视化工具

- [MistTrack](https://misttrack.io/)
- [ethtx.info](https://ethtx.info/)
- [Front-running explorer](https://zeromev.org/)
- [Phalcon BlockSec](https://phalcon.blocksec.com/?s=09)
- [Bitquery Explorer](https://explorer.bitquery.io/)
- [Tx eth samczsun](https://tx.eth.samczsun.com/)
- [Tenderly](https://tenderly.co/)
- [Sentio](https://app.sentio.xyz/explorer)
- [Socketscan](https://socketscan.io/)
- [3D VR blockchain visualization](https://ethresear.ch/t/open-source-3d-and-vr-blockchain-visualizations/3297/2)
- [eigenphi.io](https://eigenphi.io/)
- [nansen.ai](https://nansen.ai)
- [**Officer CIA’s Investigation tools list**](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)


### Toke 流程可视化

- [breadcrumbs.app](https://www.breadcrumbs.app/)
- [bloxy.info](https://bloxy.info/)
- [ethtective.com](http://ethtective.com/)


### 杂项工具

- [ETH Toolbox](https://eth-toolbox.com/)
- [DethCode](https://github.com/dethcrypto/dethcode)
- [Cryptocurrencies OSINT](https://start.me/p/ek4rxK/cryptocurrency-osint)
- [DeBank](https://debank.com/)
- [Tutela](https://tutela.xyz/)

---

## 智能合约审计工具

### 测试框架

- [Foundry](https://github.com/foundry-rs/foundry)
- [Hardhat](https://hardhat.org/)
- [Brownie](https://eth-brownie.readthedocs.io/en/stable/)
- [Truffle](https://trufflesuite.com/)

### Fuzzers

- [Echidna](https://github.com/crytic/echidna)
- [Foundry Fuzz](https://book.getfoundry.sh/forge/fuzz-testing)
- [ChainFuzz](https://github.com/ChainSecurity/ChainFuzz)
- [Harvey](https://mariachris.github.io/Pubs/FSE-2020-Harvey.pdf)
- [sFuzz](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=6068&context=sis_research)

### VS Code 插件

- [Solidity Visual Developer](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor)
- [Slither VSC](https://marketplace.visualstudio.com/items?itemName=trailofbits.slither-vscode)
- [Inline Bookmarks](https://github.com/tintinweb/vscode-inline-bookmarks)
- [Solidity Metrics](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-metrics)
- [EthOver](https://marketplace.visualstudio.com/items?itemName=tintinweb.vscode-ethover)
- [GraphViz Interactive Preview](https://marketplace.visualstudio.com/items?itemName=tintinweb.graphviz-interactive-preview)
- [Mythx VSC](https://marketplace.visualstudio.com/items?itemName=MythX.mythxvsc)
- [Remix VSC](https://marketplace.visualstudio.com/items?itemName=RemixProject.ethereum-remix)

### 格式化及格式检查

- [EthLint](https://github.com/duaraghav8/Ethlint)
- [solidity-coverage](https://github.com/sc-forks/solidity-coverage)
- [Prettier](https://prettier.io/) + [Solidity Plugin](https://github.com/prettier-solidity/prettier-plugin-solidity)
- [Doc-Gen](https://mtmacdonald.github.io/docgen/docs/index.html)
- [Solhint](https://github.com/protofire/solhint)
- [sol function profiler](https://github.com/EricR/sol-function-profiler)
- [BSOL](https://github.com/Giulio2002/bsol) 一个为Solidity代码片段和智能合约编写基准测试的工具

### 可视化工具

- [Solidity Visual Developer](https://marketplace.visualstudio.com/items?itemName=tintinweb.solidity-visual-auditor)
- [Sūrya](https://github.com/ConsenSys/surya)
- [Solgraph](https://github.com/raineorshine/solgraph)
- [EVM Lab](https://github.com/ethereum/evmlab)
- [Ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger)

### 动静态分析

- [Slither](https://github.com/crytic/slither)
- [MythX](https://mythx.io/)
- [Mythril](https://github.com/ConsenSys/mythril)
- [Manticore](https://github.com/trailofbits/manticore)
- [securify2](https://github.com/eth-sri/securify2)
- [Eth Security Toolbox](https://github.com/trailofbits/eth-security-toolbox)
- [smartcheck](https://github.com/smartdec/smartcheck)
- [solidityscan.com](https://solidityscan.com/)
- [Fuzzinglab’s Octopus](https://github.com/FuzzingLabs/octopus)
- [Pakala](https://github.com/palkeo/pakala) 以太坊攻击性漏洞扫描器，详见[使用Pakala窃取以太坊](https://www.palkeo.com/en/projets/ethereum/stealing_ether.html)
- [Karl](https://github.com/cleanunicorn/karl) 智能合约安全漏洞检查工具
- [Verisol](https://github.com/microsoft/verisol) 来自微软的Solidity智能合约的正式验证和分析工具

### 审计指南

- [The Auditors Book](https://theauditorbook.com/)
- [Solodit.xyz](https://solodit.xyz/dashboard)
- [Audit Hero](https://audit-hero.com/search-findings)
- [Solidity Attack Vectors](https://github.com/Quillhash/Solidity-Attack-Vectors)
- [Audit Checklist](https://github.com/tamjid0x01/SmartContracts-audit-checklist)
- [Awesome Solidity Gas Optimizations](https://github.com/iskdrews/awesome-solidity-gas-optimization)
- [Secureum Blogs](https://substack.com/profile/23643769-rajeev-secureum)
- [Diligence - Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/attacks/)
- [Blockchain Hacking QuickStart Guide](https://start.blockchainhax.com)
- [How to Become a Smart Contract Auditor by Cmichel](https://cmichel.io/how-to-become-a-smart-contract-auditor/)

---

## 钱包安全
- [Stelo Labs](https://stelolabs.com/)
- [BlowFish](https://blowfish.xyz/)
- [Pocket Universe](https://www.pocketuniverse.app/)
- [Wallet Guard](https://walletguard.app/)
- [Interlock](https://www.interlock.network/)
- [Revoke.cash](https://revoke.cash/)
- [Novus](https://www.usenovus.io)
- [Web3 Antivirus](https://web3antivirus.io/)
- [PeckShield Alert](https://chrome.google.com/webstore/detail/peckshieldalert/dakkielolpafjbgnjnakddabmbbkcioe)


### 更多参考

[https://github.com/OffcierCia/On-Chain-Investigations-Tools-List](https://github.com/OffcierCia/On-Chain-Investigations-Tools-List)   
[https://github.com/shantanhunt/Smart-Contract-Auditor-Tools-and-Techniques](https://github.com/shantanhunt/Smart-Contract-Auditor-Tools-and-Techniques)   
[https://github.com/Anugrahsr/Awesome-web3-Security](https://github.com/Anugrahsr/Awesome-web3-Security) </br>
[https://github.com/RektifyAI/auditing-demystified](https://github.com/RektifyAI/auditing-demystified)

