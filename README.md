## Magento 2 Hungarian Language Pack

**Install Hungarian pack**:

``` php
composer require aveadev/magento-2-hungarian-language-pack:dev-master
php bin/magento setup:static-content:deploy hu_HU
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush
```
