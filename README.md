# 🛒 Shopibar
Shopify Admin Plugin for [Bitbar](https://github.com/matryer/bitbar#-bitbar--)


![preview](http://i.imgur.com/Dt499Nh.png "Preview")


## Usage

1. Copy `Shopibar.15m.js` file to your BitBar plugins directory. For details click [here](https://github.com/matryer/bitbar#installing-plugins).

2. Shopibar plug-in uses Shopify Admin API. In order to use the plug-in you need to create a `Private App` in Shopify Admin page. Visit `yourShopName.myshopify.com/admin/apps/private` to create an app. 
Shopibar private app needs following permission (Read Access):
* Store content like articles, blogs, comments, pages, and redirects
* Customer details and customer groups
* Orders, transactions and fulfillments
* Products, variants and collections

3. Add your `Api Key` and `Password` to `Shopibar.15m.js` file. 

4. Give necessary permissions using `chmod +x Shopibar.15m.js`command in terminal.



## Version History

### v1.0.2
- New: Options for turning on/off of visibility for pending orders, unshipped orders and customer count

### v1.0.1
- Fix: Total order price ([issue #1](https://github.com/m-etka/Shopibar/issues/1))

### v1.0
- Shows customer count
- Shows pending orders with details

