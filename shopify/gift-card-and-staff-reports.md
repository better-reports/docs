# Gift card and staff reports

If your store is on the _Shopify Plus_ plan, Shopify provides access to additional APIs to load Gift cards and Users. Unfortunately, these two APIs must be activated manually (more on that below).

{% hint style="info" %}
If your store is not on the Shopify Plus plan, the gift card and users API are not available.\
As a result, gift card reports are not possible.\
However, you can record your team members manually. See [Record staff](showing-staff-names.md).
{% endhint %}

### Gift card reports

Interesting Gift Card reports include:

* Active gift cards
* Expiring gift cards
* Monthly issued gift cards
* Remaining gift card balance by expiry month

Any many more.

### Users API and team member names

The Users API will enable Better Reports to record the names of all team members configured on your store.\
It can be useful if you want to segment your report by individual staff members.\
If you operate physical stores (brick and mortar), you could for example show **total sales by staff member, by location**.

### Activating the Gift cards and/or Users APIs

Shopify doesn't allow "public apps" to use the [Gift cards](https://shopify.dev/docs/admin-api/rest/reference/plus/giftcard) and [Users](https://shopify.dev/docs/admin-api/rest/reference/plus/user) API and a custom app must be created for your specific store. Here's how we can set this up for you -

a) Email our friendly staff at [hello@betterreports.com](mailto:hello@betterreports.com). Simply state that you want to activate gift cards (or user reports)

{% hint style="warning" %}
You may have to contact your Shopify Plus Success Manager to activate the **Users** **API** for your store.
{% endhint %}

b) We will create a custom app **specific for your store** requesting gift card (and users if needed) permissions and email you an install link for the custom app. The custom app must be installed within 7 days of generating the link.

![Install screen of the custom app](<../.gitbook/assets/image (85).png>)

c) Once you install the app on your store, you will be redirected to Better Reports app and the gift cards reports (and optionally users reports) would be enabled.\


![Confirmation message of gift card data being enabled.](<../.gitbook/assets/image (81).png>)



{% hint style="info" %}
After the setup, there will be two apps with the name of Better Reports on your store.&#x20;

The Better Reports Gift Cards/Users app will have a Custom tag and must remain installed for the Gift Card/Users sync to work.

\
![](<../.gitbook/assets/image (84).png>)
{% endhint %}
