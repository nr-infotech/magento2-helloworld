# Hello World for beginner for better understanding of how beginner can start first module in magento2

# How to install this extension?

Under your root folder, run the following command lines:

- composer require nr-infotech/magento2-helloworld
- php bin/magento setup:upgrade --keep-generated
- php bin/magento setup:di:compile
- php bin/magento cache:flush

# How to see the results

1. Go to the storefront and type in url after your site's base url

base_url/helloworld

