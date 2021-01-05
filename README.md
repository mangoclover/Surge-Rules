# 简介

本项目生成适用于 [**Surge**](https://nssurge.com) 的规则集（DOMAIN-SET 和 RULE-SET）。使用 GitHub Actions 每小时自动构建，保证规则最新。

## 说明

本项目的所有规则集（DOMAIN-SET 和 RULE-SET）均来自上游列表。

### ⚠️ 注意：

- **DOMAIN-SET** 同时适用于 Surge for Mac **v3.5.1** 及更新的版本、Surge for iOS **v4.2.2** 及更新的版本，拥有比 RULE-SET 更优秀的匹配效率，建议优先使用。
- **RULE-SET** 同时适用于 Surge for Mac **v3.0** 及更新的版本、Surge for iOS **v3.4** 及更新的版本。

## 规则文件地址及使用方式

### 规则文件地址

源代码在master branch  生成规则集在release branch下载

> 除通过域名 `raw.githubusercontent.com`访问外，也可以通过使用`cdn.jsdelivr.net`访问规则文件，且已针对 `jsdelivr` 作强制清除CDN缓存处理，保证最新性。

### 使用方式

关于 Surge 的详细使用方法，见[官方手册](https://manual.nssurge.com)。

## 致谢

- [@Loyalsoldier](https://github.com/Loyalsoldier/surge-rules)
- [@DivineEngine](https://github.com/DivineEngine/Profiles/tree/master/Surge/Ruleset)
- [@privacy-protection-tools](https://github.com/privacy-protection-tools/anti-AD)
- [@geekdada](https://github.com/geekdada/surge-list)
