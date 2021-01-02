# 简介

本项目生成适用于 [**Surge**](https://nssurge.com) 的规则集（DOMAIN-SET 和 RULE-SET）。使用 GitHub Actions 每小时自动构建，保证规则最新。

## 说明

本项目的所有规则集（DOMAIN-SET 和 RULE-SET）均来自上游列表。

### ⚠️ 注意：

- **DOMAIN-SET** 同时适用于 Surge for Mac **v3.5.1** 及更新的版本、Surge for iOS **v4.2.2** 及更新的版本，拥有比 RULE-SET 更优秀的匹配效率，建议优先使用。
- **RULE-SET** 同时适用于 Surge for Mac **v3.0** 及更新的版本、Surge for iOS **v3.4** 及更新的版本。

## 规则文件地址及使用方式

### 在线地址（URL）

> 如果无法访问域名 `raw.githubusercontent.com`，可以使用第二个地址（`cdn.jsdelivr.net`），其中已针对 `jsdelivr` 作强制清除CDN缓存处理，保证最新性。

### 代码及下载
源代码在master branch 
生成规则集在release branch下载

### 使用方式

关于 Surge 的详细使用方法，见[官方手册](https://manual.nssurge.com)。

## 致谢

- [@Loyalsoldier/surge-rules](https://github.com/Loyalsoldier/surge-rules)-参考了 `run.yml` 部分代码
- [@DivineEngine/Profiles](https://github.com/DivineEngine/Profiles/tree/master/Surge/Ruleset)-引用了 `Surge/Ruleset/Unbreak.list` 部分代码
- [@privacy-protection-tools](https://github.com/privacy-protection-tools/anti-AD)-引用了 `anti-AD/anti-ad-surge2.txt` 部分代码
