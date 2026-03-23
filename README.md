# WooCommerce subscriptions-core

Community-maintained fork of [Automattic/woocommerce-subscriptions-core](https://github.com/Automattic/woocommerce-subscriptions-core) (archived May 2025).

This package is a code library, itself depending on [WooCommerce](https://woocommerce.com/download/), which powers core subscriptions related functionality in:

 - [WooCommerce Subscriptions](https://woocommerce.com/products/woocommerce-subscriptions/), a paid extension
 - [WooCommerce Payments](https://woocommerce.com/products/woocommerce-payments/), a free payment gateway (with transaction fees)

## Changes from upstream

- Updated `composer/installers` requirement to support v2 (`^1.2 || ^2.2`)
- Removed restrictive `config.platform.php` override
