# Cost of goods sold (COGS)

Be sure to [record your product variant costs](https://shopify.com/admin/bulk?resource\_name=ProductVariant\&show=image%2Cfull\_title%2Csku%2Cprice\&edit=cost) in Shopify so that Better Reports can compute your Cost of Goods Sold and Gross Margin accurately.

$$
Cost\ of\ Goods\ Sold = Product\ variant\ cost × quantity
$$

$$
Gross\ Margin = Net\ sales\ −\ Cost\ of\ Goods\ Sold
$$

$$
Gross\ Margin (\%) = Gross\ Margin\ /\ Net\ sales × 100
$$

****

#### How is COGS computed when product cost is unspecified?

If the product cost is unknown, Better Reports cannot compute COGS. In such cases, the built-in formula assumes that COGS is equal to Net Sales, resulting in a 0% margin.\
As a consequence, your COGS is overstated and your gross margin is understated. This is an arbitrary choice, used as a conservative measure. You could easily create your own COGS and Gross Margin measures to achieve a different outcome. For example, your formula might assume that, if the product cost is unknown, the gross margin should be set to 10% arbitrarily.

A **cost of $0 is not the same as an unspecified cost**. A cost of $0 means your COGS is $0 and therefore your gross margin is 100%. This is often the case for digital products (an eBook for example).

{% hint style="warning" %}
Shopify doesn't record the historical cost of product variants  (as of the date of the order).\
As a result, COGS is always computed using the latest / current product costs.\
For this reason, any time you update a product cost, all historical COGS amounts are updated immediately in all reports.\
Another consequence is that if you delete a variant, it won't be possible to compute COGS anymore for that variant, because its cost cannot be retrieved anymore.
{% endhint %}
