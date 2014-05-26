INTRODUCTION
------------
* The TrustPay Commerce (commerce_trustpay) module allows you to configure your 
site to process payments through TrustPay Gateway API.

REQUIREMENTS
------------
* The TrustPay module depends on the following modules being installed and enabled:
    - commerce
    - commerce_payment
    - commerce_ui
    - commerce_order
    - commerce_payment_ui

INSTALLATION
------------
Unpack the module package(tar.gz/zip) unto your modules folder (e.g sites/all/modules/)

Enable the module in your module configuration page or alternatively using drush 
(e.g drush pm-enable commerce_trustpay).

CONFIGURATION
-------------
* With the Commerce Module fully integrated, go through to the payment method configuration
page to enable the TrustPay payment module.

* Once enabled, edit the TrustPay module and under "Actions" edit the Payment Settings with
the following parameters:
    - Vendor ID = This is your vendor_id from TrustPay (http://my.trustpay.biz) associated 
            with your registered application.
    - Custom Success URL = This is an alternative URL you may wish to be the endpoint for 
                        successful payments.
    - Custom Cancel URL = This is an alternative URL you may wish to be the endpoint for 
                        canceled payments.

MAINTAINERS
-----------
Current maintainers:
 * Zipho Mashologu (zipho) - https://drupal.org/user/334030
This project has been sponsored by:
 * TrustPay
  TrustPay™ (http://www.trustpay.biz) enables developers to monetise their M/E-commerce solutions, globally.
  

