---
description: >-
  The CustomerList entity represents a collection Customer objects. This
  collection can typically be sorted, paged, and refined.
---

# CustomerList



| **Field** | **Type** | **Description** |
| :--- | :--- | :--- |
| id | String | Unique identifier of customer list. |
| title | String | Title of customer list. |
| customers | Array | Collection of [Customer](customer.md) objects. |
| pager | Object | Object that controls customer list paging . |
| sorter | Object | Object that control sorting through the customer list |

{% hint style="info" %}
**Pager Object**: holds specific properties that allow the CustomerList to be paged.

* **pageSize**:  number of customers to return per page
* **totalItems**: total number of customers in CustomerList
* **startItem**:  integer location of first customers \(zero-index based\)
* **nextPageUrl**: Some systems provide a simple url to get next set of batched results
{% endhint %}



{% hint style="info" %}
**Sorter** **Object**: holds specific properties that allow the CustomerList to be sorted.

* fieldName:  field name used to sort CustomerList
* type: sort type, ASC or DESC
{% endhint %}

