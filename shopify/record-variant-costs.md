# Record variant costs

In Shopify, cost is maintained at the variant level and the way COGS \(calculated as variant cost x quantity sold\) works is that it always takes the latest data from variant costs.

This is different than Shopify's built-in COGS reporting that will not update if cost is entered after a sale.

However, because Shopify does not record historical cost data, there is no way for us to measure how much the cost of a product was when it was sold.

In Better Reports, as a conservative measure, variants without a cost will incur 100% cost of goods sold and 0% gross margin \(Cost of goods sold = Net sales\).

However, you can [record your variant costs](https://shopify.com/admin/bulk?resource_name=ProductVariant&show=image%2Cfull_title%2Csku%2Cprice&edit=cost) in Shopify to rectify this. You can see the link at the top when you visit the built-in report 'All times sales' or any other report with COGS data.

![](../.gitbook/assets/image%20%2851%29.png)

You can refer to the built-in 'Variants without cost' report that shows a list of variants without cost recorded. The report will update and show the current cost once you have updated the costs in Shopify. 

If you have a preferred calculation of COGS for variants without cost recorded, feel free to reach out to us at [hello@betterreports.com](mailto:hello@betterreports.com)! We'd be happy to help you create custom COGS fields with your preferred calculation.

