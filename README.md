# Hello World for beginner for better understanding of how beginner can start first module in magento2

# How to install this extension?

Under your root folder, run the following command lines:

If you want to install latest version then run below command
- composer require nr-infotech/magento2-helloworld

If you want to install specific version then run below command
- composer require nr-infotech/magento2-helloworld:1.0.1

Ypu can check all versions by below command 
- composer show --all nr-infotech/magento2-helloworld

Below command will register your module
- php bin/magento setup:upgrade --keep-generated

Flush your cache by below command
- php bin/magento cache:flush

# How to see the results

1. Go to the storefront and type in url after your site's base url

base_url/helloworld

