# ProductList

> The ProductList entity represents a collection of related product objects.  This collection can typically be sorted, paged, and refined.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- |
| id | String | Unique identifier of product category. |
| title | String | Title of product category. |
| products | Array | Collection of [Product](product.md) objects. |
| refinements | Object | Collection of filter objects. |
| pager | Object | Object that controls product category paging . |
| sorter | Object | Object that control paging through the products array/ |

{% hint style="info" %}
**Refinements Object: **holds specific properties that allow the ProductList to be further refined or filtered.

* label
* options: \[ { name, id, path, selected  } \]
{% endhint %}

{% hint style="info" %}
**Pager Object**:  holds specific properties that allow the ProductList to be paged.

* pageSize:  number of products to return per page
* totalItems: total number of products in ProductList
* startItem:  integer location of first product \(zero-index based\)
{% endhint %}

{% hint style="info" %}
**Sorter** **Object**: holds specific properties that allow the ProductList to be sorted.

* fieldName:  field name used to sort ProductList
* type: sort type, ASC or DESC
{% endhint %}

  






