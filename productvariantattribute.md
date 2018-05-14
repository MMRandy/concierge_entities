# ProductVariantAttribute

> ProductVariantAttributes are properties like 'color' and 'size' that can be used to create variations of the original master product.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- |
| id | String | The id of the variation attribute. |
| name | String | The display name of the variation attribute. |
| type | String | Variant attribute type \('string', 'int'\) |
| values | Array | A collection of values specific to this attribute. |

{% hint style="info" %}
**Value Array**:  a listing of possible values for the product variant attribute.  For example, if a variant attribute was "color", this array would potentially hold "red", "blue", and "green".
{% endhint %}

