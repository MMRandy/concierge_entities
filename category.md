# Category

> The Category object represents a named grouping of related products.  Each Category can represent a collection of products or a collection of child Categories.  Categories are typically organized in a nested, hierarchical structure that and form the basis of navigating a company's products.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- |
| label | String | Short description of item. |
| id | String | Unique id for menu item. |
| subCategories | Array  | Array of Category objects. |

{% hint style="info" %}
**SubCategories Array**: 

This will be an array of Category objects.  If the subCategories property is null, the id field will be used to retrieve a collection of related products.  Otherwise the subCategories array will expose a deeper nested collection of Category objects.
{% endhint %}





