# WooCommerce-Validation-Collection

このリポジトリは、WooCommerceプラグインとWooCommerce for Japanプラグインとcustomer-reviews-woocommerceとyith-woocommerce-wishlistのバリデーション関連ファイルを収集し、整理したものです。登録フォームのカスタマイズに必要な検証ルールを把握し、開発効率の向上を目指します。

## リポジトリ構成
WooCommerce-Validation-Collection/
├── woocommerce/
│   ├── class-wc-validation.php
│   ├── ValidationContext.php
│   ├── ValidationError.php
│   ├── ValidationResult.php
│   ├── ValidationUtils.php
├── woocommerce-for-japan/
│   ├── ValidationException.php
│   ├── ValidationFailedExceptionInterface.php
│   ├── ValidationFailedExceptionInterfaceTest.php
│   ├──ValidationFailedExceptionInterface.php
│   │    ├──Validation
│   │         ├──CheckoutFormValidator.php     
│   ├── validation-interface
│        ├──validation-interface
│            ├──.env.example
│            ├──CHANGELOG.md
│            ├──LICENSE
│            ├──phpcs.xml.dist
│            ├──psalm.xml.dist
│            │
│            ├──src
│            │    ├──ValidatorInterface.php 
│            │    ├──Exception
│            │        ├──ValidationFailedExceptionInterface.php
│            ├──tests
│                ├─bootstrap.php
│                ├──unit
│                    ├──ValidatorInterfaceTest.php
│                    ├──Exception
│                       ├── ValidationFailedExceptionInterfaceTest.php   
├── customer-reviews-woocommerce/
│   ├── ValidationResult.php
├── yith-woocommerce-wishlist/
│   ├──yith-bh-onboarding.js
│   ├── yith-bh-onboarding.min.js
├── README.md

## 使い方

各ディレクトリには、それぞれのプラグインのバリデーション関連ファイルが格納されています。

