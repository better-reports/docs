# What is a connector

A connector is what enables Better Reports to connect to a specific app, API or other online service.

A connector is responsible for:

#### Securely authenticating with the app

When you first connect an app, you will be prompted to grant access.

#### Importing the app data

Once authenticated, the connector will start importing your app's data.  
Depending on the amount of data, the initial import might take a few seconds or a few hours.

#### Keeping your data in sync

The initial data import is a one-off operation. Once complete, Better Reports is always working in the background to monitor any changes that occur in your connected app and propagate these changes into your reports so that they are always accurate.

Depending on the app, a different mechanism may be employed to keep your data in sync.

Most modern apps \(such as Stripe, Shopify, QuickBooks Online\) will notify Better Reports in real-time whenever something changes \(thanks to so-called [webhooks](https://en.wikipedia.org/wiki/Webhook)_\)_. As a result, your reports are always up-to-date.  
For apps that don't support webhooks, the connector will poll your data several times a day. As a result, there might be a delay between the time when a change occurs in your connected app, and the time when this change is reflected in your reports.

#### Deleting your data

If you disconnect your app, the connector will immediately delete your app's data permanently. That being said, you can reconnect at any time.

**The data model & built-in reports**

Each connector comes with a data model, which represents the various entities and how they are related. \(For example, the Shopify data model is made of Orders, Customers, Products, etc...\). A connector also provides commonly used built-in reports out of the box.

#### Billing

Billing occurs at the connection level. Each connector has a slightly different pricing model, and most offer a free trial. Each organization is billed monthly for all connections that were active during the month. For further details, please check the pricing for individual [connectors](https://www.betterreports.com/connectors).

