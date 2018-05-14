# Customer

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| id | String | primary key |
| firstName | String | First name of customer |
| middleName |  String | Middle name or initial of customer |
| lastName |  String | Last name of customer |
| attributes | Array of [CustomerAttribute ](customerattribute.md) | Custom attributes about customer |
| phone | Array of **Phone **Objects | Phone numbers for customer |
| email | Array of **EmailAddress **Objects | Emails for customer |
| address | Array of **Address **Objects | Addresses for customer |
| contactPreference | Array of **Preference **Objects | Customers chosen form of communication |
| customerSince | Date | Date of customer creation |



{% hint style="info" %}
**EmailAddress Object**

* email: String \( Ex: rbrown@madmobile.com \)
* display: String \( Ex: Randy Brown \)
* primary: Boolean
{% endhint %}

{% hint style="info" %}
**Phone Object**

* number: String
* type: String \(Mobile, Home, Work, etc\)
* isPrimary: Boolean
{% endhint %}

{% hint style="info" %}
**Address Object**

* street: String
* city: String
* state: String
* zip: String
* country: String
{% endhint %}

{% hint style="info" %}
**Preference Object**

* contactType: String \(Text, Phone, Email, etc\)
* permission: Boolean
{% endhint %}





