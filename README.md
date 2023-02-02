# Magento Arabic Language Package <ar_EG>

Salaam, this is an Arabic language package for magento <ar_EG> you can install it via composer by following the next steps.

## Installation

Add GitHub repo to composer.json:
    
    composer config repositories.lastcoming-magento-language-package-ar_eg git "https://github.com/lastcoming/magento-language-package-ar_eg.git"

Install the language package:
    
    composer require lastcoming/magento-language-package-ar_eg

Now that the language package is successfully installed run: 
    
    bin/magento setup:upgrade

> #### At Backend Change Your Locale to Arabic (Egypt)
>
> - STORES > Configuration > General > Locale Options > Locale > Arabic (Egypt)
>

## Uninstallation

To remove/uninstall the package:

    bin/magento i18n:uninstall lastcoming/magento-language-package-ar_eg