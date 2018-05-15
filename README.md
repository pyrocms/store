# Store

The default store bundle for Pyro.

### Until we finish our plan for distribution please install manually as described below.

Copy the project requirements to your `composer.json` file and run `composer update`. Be sure to use `--prefer-source` if you plan to contribute.

Then install all the addons with the following artisan commands:

```bash
php artisan addon:install anomaly.module.store
php artisan addon:install anomaly.module.carts
php artisan addon:install anomaly.module.taxes
php artisan addon:install anomaly.module.orders
php artisan addon:install anomaly.module.products
php artisan addon:install anomaly.module.shipping
php artisan addon:install anomaly.module.checkouts
php artisan addon:install anomaly.module.customers
php artisan addon:install anomaly.extension.basic_checkout
php artisan addon:install anomaly.extension.flat_rate_shipping_method
```
