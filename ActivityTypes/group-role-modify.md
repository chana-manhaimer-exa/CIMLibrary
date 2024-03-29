group-role-modify
=================

Description
-----------
The security role association of a group was modified directly

The possible fields for this activity type will vary depending on whether the activity was a [success](#group-role-modifysuccess) or a [fail](#group-role-modifyfail).

| Parameter     | Value             |
| ------------- | ----------------- |
| Subject       | group             |
| Activity      | role-modify       |
| Activity Type | group-role-modify |
| Pretty Name   | Group Role Modify |
| Legacy Name   |                   |

group-role-modify:success
-------------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |

group-role-modify:fail
----------------------

| Field     | Core | Detection | Informational |
| --------- | ---- | --------- | ------------- |
| role_name |      |           | &#10003;      |