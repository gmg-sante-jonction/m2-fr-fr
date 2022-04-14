## Magento 2 French Language Pack

## 1. How to Install French Language Pack
Install the French language pack via composer is never easier.

**Install French pack**:
composer require gmg-sante-jonction/m2-fr-fr:dev-master
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

**Update  French pack**:

```
composer update gmg-sante-jonction/m2-fr-fr:dev-master
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```m2-fr-fr
m2-fr-fr
m2-fr-fr
m2-fr-fr
m2-fr-fr
