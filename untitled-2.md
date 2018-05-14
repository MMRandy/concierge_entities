# CustomerTransaction

> The CustomerTransaction object represents a prior sales transaction for the customer.  This transaction could be either an e-commerce or store sales transaction.

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| id | String | Unique identifier for customer transaction. |
| storeId | String | The store id where the transaction occurred. |
| transactionDate | DateTime | Date of Transaction. |
| transactionNumber | string | Unique identifier for the customer transaction. |
| total | decimal | Total monetary value of the transaction. |
| totalitems | integer | Total number of items sold in the transaction. |
| lineItems | Array | Collection of POS line items sold for this transaction |

{% hint style="info" %}
**LineItems Array**:  a collection of product items that were sold for a specific customer transaction.  This listing typically contains POS line item information, but may also be augmented with richer e-commerce date.

* itemId \(or POS SKU\)
* unitPrice
* quantity
* imageUrl
* name
* shortDescription
{% endhint %}



