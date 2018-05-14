# Category

> The Category entity represents a collection of related product objects.  This collection can typically be sorted, paged, and filtered.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- |
| id | String | unique identifier of product category |
| title | String | title of product category |
| products | Array | collection of [Product](product.md) objects |
| filters | Array | collection of filter objects |
| pager | Object | object that controls product category paging  |

