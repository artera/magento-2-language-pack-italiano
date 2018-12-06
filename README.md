## Magento 2 Language Pack Italiano
Italian Language Package for Magento 2.x (it_IT) from [Artera](https://www.artera.it/) team.

This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/it#/Head) at Crowdin and based on the latest Magento sourcefiles.

### 1. Install Italian Language Package
We explain two different methods to install this Language Package.
We reccomended use it on your Magento projects with Composer.


#### Method #1. With Composer (Recommend - is required Authentication)

**Install Italian package**
```
composer require artera/magento-2-language-pack-italiano
php bin/magento setup:static-content:deploy it_IT
php bin/magento cache:flush
```

**Update Italian package**
```
composer update artera/magento-2-language-pack-italiano
php bin/magento setup:static-content:deploy it_IT
php bin/magento cache:flush
```


#### Method #2. Download Package and Upload Locally (Not recommended)

**Download Italian package**
Download our Language Package from this repository.

**Upload Italian package**
Create these subdirectories path in your magento root folder like **[Your_Magento_Root]**`/app/i18n/Artera/language-it_it/`
Unzip the Italian Language Package here.

**Flush cache**
From Magento 2 admin panel here:
`System > Cache Management > Flush Magento Cache`

Or flush cache from Command Line:
```
php bin/magento cache:flush
```

### 2. Active Italian Language Package
Now active the Italian Language Package for your Magento 2 store.

Activate Italian from Magento 2 admin panel here:
- `Stores > Configuration > General > General > Locale Options`
- `My Account > Account Information > Interface Locale` *(admin panel translation)*


## License
[The OSL-3.0 License](http://opensource.org/licenses/OSL-3.0)
