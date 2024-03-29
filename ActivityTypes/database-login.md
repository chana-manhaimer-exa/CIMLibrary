database-login
==============

Description
-----------
A user logged in to a database

The possible fields for this activity type will vary depending on whether the activity was a [success](#database-loginsuccess) or a [fail](#database-loginfail).

| Parameter     | Value          |
| ------------- | -------------- |
| Subject       | database       |
| Activity      | login          |
| Activity Type | database-login |
| Pretty Name   | Database Login |
| Legacy Name   |                |

database-login:success
----------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |

database-login:fail
-------------------

| Field  | Core     | Detection | Informational |
| ------ | -------- | --------- | ------------- |
| domain |          | &#10003;  |               |
| user   | &#10003; | &#10003;  |               |