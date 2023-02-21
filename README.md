SpectroCoin Bitcoin Payment Extension
---------------

**MOVED**

Up to date version can be found in [SpectroCoin Magento Repo](https://github.com/SpectroCoin/Magento-Bitcoin-Payment-Gateway-Extension) or [SpectroCoin Magento 2 Repo](https://github.com/SpectroCoin/Magento-2-Bitcoin-Payment-Gateway-Extension)

---------------

This module integrates [SpectroCoin](https://spectrocoin.com/) Payments with [Magento](http://magento.com/) to accept [Bitcoin](https://bitcoin.org) payments.

**INSTALLATION**

1. Upload files to Magento main folder.
2. Generate private and public keys [Manually]
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
3. Generate private and public keys [Automatically]
	1. Private key/Public key:
	Go to [SpectroCoin](https://spectrocoin.com/) -> [Project list](https://spectrocoin.com/en/merchant/api/list.html)
	Click on your project  -> Edit Project -> Click on Public key (You will get Automatically generated private key, you can download it. After that and Public key will be generated Automatically.)
    
**CONFIGURATION**

1. Go to System -> Configuration -> Payment Methods -> SpectroCoin.
2. Enter your Merchant Id, Application Id, Private key.

**BENEFITS**
 
1. Accept Bitcoin payments.
2. Fully automatic operation.
3. Automatic conversion to bitcoin via realtime exchange rate feed and calculations.
4. Lookup SpecroCoin transaction details.

**INFORMATION** 

1. You can contact us e-mail: info@spectrocoin.com.
2. You can contact us by phone: +442037697306.
3. You can contact us on Skype: spectrocoin_merchant.
