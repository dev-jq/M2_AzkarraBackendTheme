# 'Azkarra' Admin M2 Theme FREE
Magento 2 Backend (dashbord) theme (black & orange) 

## Screenshots
![Backend theme - login page](https://raw.githubusercontent.com/dev-jq/M2_AzkarraBackendTheme/main/README-assets/login-page.png)

![Backend theme - dashboard](https://raw.githubusercontent.com/dev-jq/M2_AzkarraBackendTheme/main/README-assets/dashboard.png)

## Installation
* Download zip file of this extension/theme
* Place all the files in your Magento 2 installation in the folders:
`app/code/jqDev/BackendAzkarraTheme` and `app/design/adminhtml/jq-dev/azkarra_backend`
* Enable the extension: `php bin/magento --clear-static-content module:enable jqDev_BackendAzkarraTheme`
* Upgrade db scheme: `php bin/magento setup:upgrade`
* Compile: `php bin/magento setup:di:compile`
* Clear cache: `php bin/magento c:f` 
