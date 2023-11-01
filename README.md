# Cookie Notification GraphQL

**Cookie Notification GraphQL is a part of MageINIC Cookie Notification extension that adds GraphQL features.** This extension extends Cookie Notification definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/module-cookienotificationgraphql

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Cookie Notification GraphQL requires installing [MageINIC Cookie Notification](https://github.com/mageinic/Cookie-Notification) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/module-cookienotification
```

## 2. How to use

- To view the queries that the **MageINIC Cookie Notification GraphQL** extension supports, you can check `Cookie Notification Graphql Extension User Guide.pdf` Or run `CookieNotification Graphql.postman_collection.json` in Postman.

## 3. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
