---
description: >-
  The CustomerList entity represents a collection Customer objects. This
  collection can typically be sorted, paged, and refined.
---

# CustomerList



| **Field** | **Type** | **Description** |
| :--- | :--- | :--- |
| id | String | Unique identifier of product category. |
| title | String | Title of product category. |
| customers | Array | Collection of [Customer](customer.md) objects. |
|  |  |  |
| pager | Object | Object that controls product category paging . |
| sorter | Object | Object that control paging through the products array |

{% hint style="info" %}
**Pager Object**: holds specific properties that allow the CustomerList to be paged.

* **pageSize**:  number of products to return per page
* **totalItems**: total number of products in CustomerList
* **startItem**:  integer location of first product \(zero-index based\)
{% endhint %}



{% hint style="info" %}
**Sorter** **Object**: holds specific properties that allow the CustomerList to be sorted.

* fieldName:  field name used to sort CustomerList
* type: sort type, ASC or DESC
{% endhint %}

