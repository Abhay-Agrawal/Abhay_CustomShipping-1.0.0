# CustomShipping Magento2 Extension 
Add Custom Shipping for magento website

# How to install

Add the module in app/code/ folder in magento root like as app/code/Abhay/CustomShipping
and run the command 
```php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```

# Check Other Magento2 Module

| Module Name | Description |
| --- | --- |
| GroupProductOptions | [Group Product With Custom Options](https://github.com/Abhay-Agrawal/Abhay_GroupProductOptions-1.0.0) |
| LatestNews | [Add Latest News Related to product offer with content in your website](https://github.com/Abhay-Agrawal/Abhay_LatestNews-1.0.0) |
