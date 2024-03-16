Magento

SkipCash offers a seamless and secure payment solution that is designed to enhance the checkout experience for your customers. This guide will walk you through the necessary steps to incorporate SkipCash’s functionality into your existing e-commerce website or mobile application. Below are the steps you will need to integrate the payment gateway.

1. First, go to Magento code that you configure in xampp/htdocs folder.
2. Then go to app directory.If there is a code directory than go into this an unzip the SkipCash Plugin File. If there is no code directory, then first create and then unzip the plugin.
3. Then open CMD as an administrator.
4. Go to Magento folder using CMD like cd C:/xampp/htdocs/magento
5. Run the following command
6. php bin/magento module:status
7. php bin/magento setup:upgrade
8. php bin/magento setup:static-content:deploy -f
9. Then after this, go to magento admin panel
10. You will find the SkipCash plugin in Payment Method.
11. Just enable it and enter your desire information.
