# 简介

本项目生成适用于 [**Surge**](https://nssurge.com) 的规则集（DOMAIN-SET 和 RULE-SET）。使用 GitHub Actions 每天早上 6:30 自动构建，保证最新性。  
This project generates rule sets (DOMAIN-SET and RULE-SET) applicable to Surge. Use GitHub Actions to automatically build at 6:30 every morning to ensure the latest.

## 说明

本项目的所有规则集（DOMAIN-SET 和 RULE-SET）均来自上游列表，主要为满足 **个人** 使用需求。  
All rule sets (DOMAIN-SET and RULE-SET) of this project are from the upstream list, mainly to meet the needs of personal use.

### ⚠️ 注意：

- **DOMAIN-SET** 同时适用于 Surge for Mac **v3.5.1** 及更新的版本、Surge for iOS **v4.2.2** 及更新的版本，专为大量域名集列表文件设计，支持上万条记录的快速查询，拥有比 RULE-SET 更优秀的匹配效率，建议优先使用。  
DOMAIN-SET is also applicable to Surge for Mac v3.5.1 and newer versions, Surge for iOS v4.2.2 and newer versions. It is designed for a large number of domain name set list files. It supports fast query of tens of thousands of records, and has more than RULE- SET is recommended for better matching efficiency.
- **RULE-SET** 同时适用于 Surge for Mac **v3.0** 及更新的版本、Surge for iOS **v3.4** 及更新的版本。  
RULE-SET is also applicable to Surge for Mac v3.0 and later versions, Surge for iOS v3.4 and later versions.

## 规则文件地址及使用方式

### 规则文件地址

源代码在 ` master branch `，生成规则集在 ` release branch ` 下载。  
The source code is in the master branch, and the generation rule set is downloaded in the release branch.

### 使用方式

关于 Surge 的详细使用方法，见[官方手册](https://manual.nssurge.com)。  
For the detailed usage of Surge, see the official manual.

## 致谢

- [@Loyalsoldier](https://github.com/Loyalsoldier/surge-rules)
- [@DivineEngine](https://github.com/DivineEngine/Profiles/tree/master/Surge/Ruleset)
- [@privacy-protection-tools](https://github.com/privacy-protection-tools/anti-AD)
- [@geekdada](https://github.com/geekdada/surge-list)
- [@felixonmars/dnsmasq-china-list](https://github.com/felixonmars/dnsmasq-china-list)
