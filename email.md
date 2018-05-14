---
description: Represents the actual email inside of an inbox
---

# InboxItem

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| id | String | Email id |
| changeKey | String |  Used to keep track of the state of an email |
| subject | String | Subject of email |
| body | String | Body of the email |
| thread | Thread Object | Thread details if available |
| importance | String | Importance of the email |
| size | Integer | Size of email |
| from | Array of EmailAddress Objects | List of from email addresses |
| to | Array of EmailAddress Objects |  List of to email addresses |
| cc | Array of EmailAddress Objects |  List of cc email addresses |
| bcc | Array of EmailAddress Objects |  List of bcc email addresses |
| isRead | Boolean | Has the email been opened |
| dateReceived | Date | Received date of email |
| hasAttachments | Boolean | If the email has attachments or not |



{% hint style="info" %}
 **EmailAddress Object**

* email: String \( Ex: rbrown@madmobile.com \)
* display: String \( Ex: Randy Brown \)
{% endhint %}

{% hint style="info" %}
**Thread Object**

* id: String
* topic: String
* index: String
{% endhint %}

