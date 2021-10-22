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

Shopify doesn't allow "public apps" to use the [Gift cards](https://shopify.dev/docs/admin-api/rest/reference/plus/giftcard) and [Users](https://shopify.dev/docs/admin-api/rest/reference/plus/user) API so you must follow these steps to create a "private app".

a) Open [https://shopify.com/admin/apps/private/new](https://shopify.com/admin/apps/private/new)

b) Input "Better Reports" for the _Private app name_

c) Input "hello@betterreports.com" for the _Emergency developer email_

d) Grant 'Read access' to _Gift cards_ and _Users_

{% hint style="warning" %}
If you can't find **Gift cards** or **Users** in the list of permissions, you may have to contact your Shopify Plus Success Manager to activate them.
{% endhint %}

e) Leave all other fields as is. It should look like this:

![](<../.gitbook/assets/image (48).png>)

![Grant 'Read access' to Gift cards and Users](<../.gitbook/assets/image (49).png>)

f) Press Save

g) Copy the Example URL (click 1 in the screenshot below)

![](<../.gitbook/assets/image (50).png>)

h) Email our friendly staff at [hello@betterreports.com](mailto:shppa\_de1068913e7d1bbf99680195b1cf215b). Simply state that you want to activate gift cards (or user reports) and paste the Example URL. This URL contains the information we need to activate your Gift card and User reports.\
That's it! You will hear from us shortly once your reports are ready.
