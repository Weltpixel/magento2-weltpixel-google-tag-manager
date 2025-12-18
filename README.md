# magento2-weltpixel-google-tag-manager

### Installation

Dependencies:
 - magento2-weltpixel-backend (see https://github.com/Weltpixel/magento2-weltpixel-backend)

With composer:

```sh
$ composer config repositories.welpixel-magento2-weltpixel-backend git https://github.com/Weltpixel/magento2-weltpixel-backend.git
$ composer require weltpixel/magento2-weltpixel-backend:dev-master

$ composer config repositories.m2-weltpixel-magento2-weltpixel-google-tag-manager git https://github.com/Weltpixel/magento2-weltpixel-google-tag-manager.git
$ composer require weltpixel/magento2-weltpixel-google-tag-manager:dev-master
```

Manually:

Important: Ensure you also install the shared Backend module. If it's already installed, you can skip this. Details in the repo at https://github.com/Weltpixel/magento2-weltpixel-backend.

Copy the zip into the app/code/WeltPixel/GoogleTagManager directory


#### After installation by either means, enable the extension by running following commands:

```sh
$ php bin/magento module:enable WeltPixel_GoogleTagManager --clear-static-content
$ php bin/magento setup:upgrade
```
