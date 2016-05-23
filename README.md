SpectroCoin Bitcoin Payment Extension
---------------

This module integrates [SpectroCoin](https://spectrocoin.com/) Payments with [Magento](http://magento.com/) to accept [Bitcoin](https://bitcoin.org) payments.

**INSTALLATION**

1. Upload files to Magento main folder.
2. Generate private and public keys
    1. Private key:
    ```shell
    # generate a 2048-bit RSA private key
    openssl genrsa -out "C:\private" 2048
    ```
    2. Public key:
    ```shell
    # output public key portion in PEM format
    openssl rsa -in "C:\private" -pubout -outform PEM -out "C:\public"
    ```

**CONFIGURATION**

3. Go to System -> Configuration -> Payment Methods -> SpectroCoin
4. Enter your Merchant Id, Application Id, Private key.
**INFORMATION** 

1. You can contact us e-mail: info@spectrocoin.com 
2. You can contact us by phone: +442037697306
 
**TITLES**

SpectroCoin-Bitcoin-Merchant-Magento-Plugin-Money-Shop-Payment
