---
description: Used by associates to store notes about the customer.
---

# Note

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- | --- |
| id | String | Primary key |
| title |  String | Title of the note |
| body |  String | Body of the note |
| parentId | String | Id of parent entity the note is attached to |
| parentType | String | Paretny type, \(Task, Customer, etc\) |
| createdBy | String | id of the associated who created the note |
| createdDate | Date | Date time of note creation |

