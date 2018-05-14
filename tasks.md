# Task

| **Field** | **Type** | **Description** |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| id | String | Primary key |
| title |  String | Title of the note |
| description |  String |  Contains a text description of the task.type |
| type | String |  The type of task, such as Call or Appointment |
| priority | String |  Indicates the importance or urgency of a task, such as high or low. |
| status | String |  The status of the task, such as In Progress or Completed |
| isClosed | boolean | If the task has been closed or not |
| assigned | Array of Strings | Array of associate ids who are assigned to the task |
| customers | Array of Strings | Array of customer ids related to the task. |
| createdBy | String | id of the associate who created the task |
| createdDate | Date | Date time of task creation |
| startDate | Date | Start date for work related to the task |
| endDate | Date | End date for work related to the task |



