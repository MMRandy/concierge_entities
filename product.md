# Product

> The Product object holds information related to a specific item for sale by a company.  A product can be of type 'item', 'master', or 'variant'.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| id | String | The id of the product or variant. |
| name | String | Display name of the product |
| short\_description | String | A short description of the product |
| long\_description | String | Detailed description of the product, the features, package contents, etc. with required formatting |
| type | String | Indicates the type of product \('master', 'item', 'variant\_group', 'variant', 'bundle', 'set'\) |
| variant\_attributes | Array | The sorted array of variant attributes assigned to the product. This is applicable for product type "master" and "variant". |
| variant\_values | Array | The variant values selected for the product in variant attribute id and value pairs. This is applicable for product types "variant" and "variation\_group" only. |
| default\_variant\_id | String | Specifies the default product variant to display. This is applicable for product type "master" only. |
| options | Array | A collection of product options available for the product \(i.e. warranty, etc\). |
| sku | String |  SKU number for the product or variant. |
| online | Boolean | Indicates whether or not product is available online |
| status | String | Used to track the state of the product |
| brand | String | The product brand identifier. |
| images | Array | A collection of product images |
| manufacturer\_name | String | The name of the product manufacturer. |
| manufacturer\_sku | String | The SKU of the product's manufacturer. |
| price | Array | An array of prices available to the product \(regular, sale, etc\). |
| upc | String | The Universal Product Code of the product. |
| primary\_category\_id | String |  The id of the products primary category.  |
| master\_id | String | If this is a product variant, this value holds the associated master product id.  |

{% hint style="info" %}
**Variant\_Attributes array:  **a collection of objects that represent possible variations on the master product object, i.e. "color", "size", etc.  The objects in this array are of type [ProductVariantAttribute](productvariantattribute.md).  Only products of type "master" and "variant" will contain this property.
{% endhint %}

{% hint style="info" %}
**Variant\_Values** **array**:  contains a collection of variant ids and values that have been set for a master product.

* id 
* value
{% endhint %}



