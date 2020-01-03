# WP Content Framework (Api module)

[![CI Status](https://github.com/wp-content-framework/api/workflows/CI/badge.svg)](https://github.com/wp-content-framework/api/actions)
[![License: GPL v2+](https://img.shields.io/badge/License-GPL%20v2%2B-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![PHP: >=5.6](https://img.shields.io/badge/PHP-%3E%3D5.6-orange.svg)](http://php.net/)
[![WordPress: >=3.9.3](https://img.shields.io/badge/WordPress-%3E%3D3.9.3-brightgreen.svg)](https://wordpress.org/)

[WP Content Framework](https://github.com/wp-content-framework/core) のモジュールです。

<!-- START doctoc -->
<!-- END doctoc -->

# 要件
- PHP 5.6 以上
- WordPress 3.9.3 以上

# インストール

``` composer require wp-content-framework/api ```

## 依存モジュール
* [controller](https://github.com/wp-content-framework/controller)

## 基本設定
- configs/config.php

|設定値|説明|
|---|---|
|api_version|APIバージョン \[default = v1]|

- configs/settings.php

|設定値|説明|
|---|---|
|use_admin_ajax|WP Rest API の代わりに admin-ajax.php を使用するかどうか|
|get_nonce_check_referer|nonce更新用API使用時にリファラをチェックするかどうか|
|check_referer_host|リファラをチェックする際に使用するホスト名|

## API の追加
今後追加予定

# Author
- [GitHub (Technote)](https://github.com/technote-space)
- [Blog](https://technote.space)
