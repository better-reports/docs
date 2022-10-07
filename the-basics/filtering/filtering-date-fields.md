# Date fields

You can filter date by fields:

* By date range (from date A to date B)
* By date part (based on the hour of day, day of week, month of year, etc...)

By default, filtering is by date range.\
If you want to filter by date part, press _Date_ (1) and select the date part you want to filter by (e.g. Day of week).

![Filter by date range or date part](<../../.gitbook/assets/image (12).png>)

## Filtering by date range

The first option is to select one of the built-in options (1), such as _Today_, _Last 7 days_, _Year to date_, etc...\
These **date ranges are dynamic**. That is, they will **automatically update as time passes**. As such, they are very useful. For example, you could create a report with a filter for _Last week_. No matter when you open this report (or when it runs as part of a schedule), **the filter will dynamically adjust** to always show the previous week's data.

Alternatively, you can use the calendar to choose a specific start/end date. The selected dates will be fixed and will NOT change automatically.

![Filter by a dynamic or fixed date range](<../../.gitbook/assets/image (13).png>)

{% hint style="info" %}
**Open your** [**organization settings**](https://app.betterreports.com/settings) **to tweak your preferred Week start/end day and timezone.**
{% endhint %}

![Organization settings](<../../.gitbook/assets/image (25).png>)

{% hint style="info" %}
For **Shopify** merchants, the above Time zone setting isn't available because Better Reports automatically aligns to the time zone the store is in.
{% endhint %}

## Filtering by date part

Less commonly, you can also filter by date part.

Let's imagine that you want to exclude Saturdays and Sundays.\
Simply select **DAY OF WEEK**, choose the _**is not**_ operator, and select _Saturday_ and _Sunday_.\
That's all it takes!

![](<../../.gitbook/assets/image (15).png>)

You can apply the exact same process with other date parts, to include or exclude:

* HOUR OF DAY - Specific hours of the day (such as outside working hours)
* MONTH OF YEAR - Specific months of the year
* QUARTER OF YEAR - Specific quarters of the year (Q1, Q2, Q3, Q4)
* YEAR NUMBER - Specific years
