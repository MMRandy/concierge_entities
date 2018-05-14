# CategoryItem

> The CategoryItem object represents a named grouping of related products.  Each CategoryItem can represent a collection of products or a collection of child CategoryItems.  CategoryItems are typically organized in a nested, hierarchical structure that and form the basis of navigating a company's categories and products.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- |
| label | String | short description of item |
| id | String | unique id for menu item |
| children | Array  | array of MenuItem objects |

{% hint style="info" %}
**Children Array**: 

This will be an array of CategoryItem objects.  If the children property is null, then the id field will typically represent, or be used to retrieve, a collection of related products.
{% endhint %}





