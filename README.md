# BITBOX API Development Guide

BITBOX, a crypto-to-crypto exchange, provides APIs for programmatic crypto trading.

Using BITBOX API, you do not have to access the BITBOX website to check your account status, trading history, or to buy and sell crypto. You can also automate your trading orders based on set criteria, such as buying a set amount of coins when the price drops by more than 5%.

This document describes basic information about BITBOX API and provides detailed examples.

> **NOTE**
>
> Visit [https://bitbox-exchange.github.io/bitbox-api-docs/](https://bitbox-exchange.github.io/bitbox-api-docs/) to read the document online.
>
> We also provide the document in [Korean](ko/).

* [Overview](/1_Overview.md)
* [Authentication and security](/2_Authentication_and_Security_Policy.md)
* [Reference](/3_Reference.md)
    * Public API
        * [Server time](/api/public/v1-public-time-get.md)
    * Market API
        * [Market coin pair policy](/api/market/v1-market-public-coins-pairPolicy-get.md)
        * [Tick values](/api/market/v1-market-public-currentTickValue-get.md)
        * [Order book](/api/market/v1-market-public-orderBooks-get.md)
        * [Market trade history](/api/market/v1-market-public-tradeHistory-get.md)
    * Trade API
        * [Limit order](/api/trade/v1-trade-limitOrders-post.md)
        * [Market order](/api/trade/v1-trade-marketOrders-post.md)
        * [Open orders](/api/trade/v1-trade-openOrders-get.md)
        * [Cancellation](/api/trade/v1-trade-orders-delete.md)
        * [Cancellation of all open orders](/api/trade/v1-trade-openOrders-delete.md)
    * Account API
        * [Balance](/api/account/v1-account-balances-get.md)
        * [Currency balance](/api/account/v1-account-balances-currency-get.md)
        * [User trade history v2](/api/account/v2-account-tradeHistory-get.md)
        * [Order information (Deprecated)](/api/account/v1-account-orders-orderID-get.md)
        * [Order information v2](/api/account/v2-account-orders-orderID-get.md)
        * [Coin transfer history](/api/account/v1-account-transactionHistory-get.md)
* [Glossary](/5_Terms.md)
* [Revision history](/0_About_This_Document.md)
* [LICENSE NOTICE](/LICENSE.md)
