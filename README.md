# WP Content Framework (Api module)

[![CI Status](https://github.com/wp-content-framework/api/workflows/CI/badge.svg)](https://github.com/wp-content-framework/api/actions)
[![License: GPL v2+](https://img.shields.io/badge/License-GPL%20v2%2B-blue.svg)](http://www.gnu.org/licenses/gpl-2.0.html)
[![PHP: >=5.6](https://img.shields.io/badge/PHP-%3E%3D5.6-orange.svg)](http://php.net/)
[![WordPress: >=3.9.3](https://img.shields.io/badge/WordPress-%3E%3D3.9.3-brightgreen.svg)](https://wordpress.org/)

[WP Content Framework](https://github.com/wp-content-framework/core) のモジュールです。

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<details>
<summary>Details</summary>

- [要件](#%E8%A6%81%E4%BB%B6)
- [インストール](#%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB)
  - [依存モジュール](#%E4%BE%9D%E5%AD%98%E3%83%A2%E3%82%B8%E3%83%A5%E3%83%BC%E3%83%AB)
  - [基本設定](#%E5%9F%BA%E6%9C%AC%E8%A8%AD%E5%AE%9A)
  - [API の追加](#api-%E3%81%AE%E8%BF%BD%E5%8A%A0)
- [Author](#author)

</details>
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

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
