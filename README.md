# Stripe
# Created by : Dhaval Kanojiya (E-commerce Architect)
Stripe payment gateway Magento2 extension
Install

    Go to Magento2 root folder

    Enter following commands to install module:

    composer config repositories.inchoostripe git https://github.com/kanojiyadhaval/magento2-Dhaval_Stripe.git
    composer require kanojiyadhaval/stripe:dev-master

    Wait while dependencies are updated.

    Enter following commands to enable module:

    php bin/magento module:enable Dhaval_Stripe --clear-static-content
    php bin/magento setup:upgrade

    Enable and configure Stripe in Magento Admin under Stores/Configuration/Payment Methods/Stripe
