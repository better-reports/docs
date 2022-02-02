# Choosing the root entity

#### **The root entity (or root table) drives which fields are usable on the report.**

In the field selector, you can choose any field from the root entity. You can also expand related entities and choose one of their fields.

#### Example:

Let's imagine a simple data model with the following entities: _Orders_, _Products_ and _Customers_

If you wanted to build a report _Total orders by month_, you would choose _Orders_ as the root entity. This way, you can use any field from the _Order_ entity __ on your report, such as the _Order Date_ and the _Total Orders_.

![Using Orders table as root entity](<../../.gitbook/assets/image (79).png>)

However, if you wanted to build a report _Total products by product type_, you would choose _Products_ as the root entity. \


![Using Products table as root entity](<../../.gitbook/assets/image (80).png>)

#### Expanding related entities

You can also use fields that belong to entities related to the root entity.\
For example, in the screenshot below, _Orders_ is the root entity. Because there is a relation between _Order_ and _Customer_, you can expand the _Customer_ table and use the _Customer status_ field on your report.

![Using fields from related entities](<../../.gitbook/assets/image (75).png>)

