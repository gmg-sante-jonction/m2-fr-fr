## Magento 2 French Language Pack

## 1. How to Install French Language Pack
Install the French language pack via composer.

```
**Install French pack**:
composer require gmg-sante-jonction/m2-fr-fr:dev-master
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

## 2. How to update French Language Pack
Update the French language pack via composer.

```
composer update gmg-sante-jonction/m2-fr-fr:dev-master
php bin/magento setup:static-content:deploy fr_FR
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```