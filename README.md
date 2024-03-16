Magento

SkipCash offers a seamless and secure payment solution that is designed to enhance the checkout experience for your customers. This guide will walk you through the necessary steps to incorporate SkipCash’s functionality into your existing e-commerce website or mobile application. Below are the steps you will need to integrate the payment gateway.

First, go to Magento code that you configure in xampp/htdocs folder.
Then go to app directory.
If there is a code directory than go into this an unzip the SkipCash Plugin File. If there is no code directory, then first create and then unzip the plugin.
Then open CMD as an administrator.
Go to Magento folder using CMD like cd C:/xampp/htdocs/magento
Run the following command
php bin/magento module:status
php bin/magento setup:upgrade
php bin/magento setup:static-content:deploy -f
Then after this, go to magento admin panel
You will find the SkipCash plugin in Payment Method.
Just enable it and enter your desire information.
