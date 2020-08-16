# Magento 2 Base theme based on luma.
Magento 2 base theme

Overview - 
------------
This theme is baracat/base theme for Magento 2 based on luma.

### Features-
* 1. Add to cart button color set to Green
* 2. Logo moved right side and Search,minicart moved to left
* 3. Alert "This is just a test." message on submission of newsletter on footer.

Installation - 
------------
### 1. Using Composer
```
composer config repositories.baracatbasetheme git git@github.com:baracat/theme-frontend-base 
composer require baracat/theme-frontend-base:dev-master
```
### 2. Using Zip File

* Download the Extension Zip File
* Extract & upload the files to /path/to/magento2/app/design/frontend/Baracat/base/

After installation by either means, enable the extension by running following commands (from root of Magento2 installation):

Then you should run Magento's setup upgrade:
```
php bin/magento setup:upgrade
```
Now you activate the Baracat/base Theme under `Content -> Design -> Configuration..`

Lastly clear Magento generated suff and caches:
```
rm -rf pub/static/frontend/
rm -rf var/view_preprocessed/css/frontend/
php bin/magento cache:clean
```

