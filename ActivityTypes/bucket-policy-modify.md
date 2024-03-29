bucket-policy-modify
====================

Description
-----------
The security policy linked to the bucket was updated

The possible fields for this activity type will vary depending on whether the activity was a [success](#bucket-policy-modifysuccess) or a [fail](#bucket-policy-modifyfail).

| Parameter     | Value                |
| ------------- | -------------------- |
| Subject       | bucket               |
| Activity      | policy-modify        |
| Activity Type | bucket-policy-modify |
| Pretty Name   | Bucket Policy Modify |
| Legacy Name   |                      |

bucket-policy-modify:success
----------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |

bucket-policy-modify:fail
-------------------------

| Field          | Core | Detection | Informational |
| -------------- | ---- | --------- | ------------- |
| policy_content |      | &#10003;  |               |