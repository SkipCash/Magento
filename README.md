Magento

SkipCash offers a seamless and secure payment solution that is designed to enhance the checkout experience for your customers. This guide will walk you through the necessary steps to incorporate SkipCash’s functionality into your existing e-commerce website or mobile application. Below are the steps you will need to integrate the payment gateway.

Step 1. Backup your web directory and store database
Step 2. Download Extension package file
Step 3. Upload & Unzip package folders to store root
Step 4. Login into SSH console & reach to store root folder:
    Open Magento Root directory & run below series of commands one by one
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy
    php bin/magento cache:flush

Step 5. From Backend,System > Cache Management.
1. Flush Magento Cache
2. Flush Cache Storage
