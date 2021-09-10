# FAQ

## Is historical inventory data available?

No. Please see [Historical inventory](historical-inventory.md).

## Is incoming inventory and inventory transfer data available?

Unfortunately not, because it's [not provided by the Shopify API](https://community.shopify.com/c/Shopify-APIs-SDKs/Make-the-transfers-API-available/td-p/494114).

## Why does the 'User name' field show a numerical ID instead of staff name?

See [Showing staff names](showing-staff-names.md)

## How is the Cost of Goods Sold computed?

See [Cost of Goods Sold](cost-of-goods-sold-cogs.md)

## Can I combine data from multiple stores?

Yes, as long as you have connected each of your stores to Better Reports.  
Please reach out to [hello@betterreports.com](mailto:hello@betterreports.com) and let us know the shop domains that you need to link together. Also, do let us know which store should be considered the _master store_.  
Once linked, whenever you open Better Reports from the _master store_, you will notice an additional field _Store_, which you can use to segment and filter your reports for any of your stores.  
  
If your stores sell in different currencies, we can also work with you to create custom measures that convert your sales to your primary currency \(you will need to supply the FX rates to be used when converting from a secondary currency to your primary currency\).

## Does Better Reports impact my online store?

No.  
Better Reports is only authorized with read-only permissions. It cannot update anything on your store.

## Is it possible to show markdown metrics?

Yes. Markdown can be computed using the difference between the variant 'Compare at price' and the 'Price'. A caveat is that whenever the 'Compare at price' is updated, all historical markdowns are immediately impacted. That is because Shopify doesn't record a historical 'Compare at price', at the time of the sale. Only the current/latest 'Compare at price' is accessible. Reach out to our friendly staff at [hello@betterreports.com](mailto:hello@betterreports.com) so we can create custom markdown metrics for your store.

## Is it possible to show shipping label / shipping cost?

No, simply because Shopify doesn't provide shipping label data in their API.  
However, it is possible to create a shipping cost metric if it is calculated using a formula \(usually based on order weight and / or shipping address\). To create a formula-based metric, please reach out to [hello@betterreports.com](mailto:hello@betterreports.com)

