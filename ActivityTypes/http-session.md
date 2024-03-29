http-session
============

Description
-----------
A summary of a complete HTTP web session

The possible fields for this activity type will vary depending on whether the activity was a [success](#http-sessionsuccess) or a [fail](#http-sessionfail).

| Parameter     | Value        |
| ------------- | ------------ |
| Subject       | http         |
| Activity      | session      |
| Activity Type | http-session |
| Pretty Name   | Http Session |
| Legacy Name   |              |

http-session:success
--------------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| referrer           |      |           | &#10003;      |
| method             |      | &#10003;  |               |
| bytes_out          |      | &#10003;  |               |
| bytes_in           |      | &#10003;  |               |
| mime               |      | &#10003;  |               |
| action             |      |           | &#10003;      |
| category           |      | &#10003;  |               |
| user_agent         |      |           | &#10003;      |
| http_response_code |      | &#10003;  |               |

http-session:fail
-----------------

| Field              | Core | Detection | Informational |
| ------------------ | ---- | --------- | ------------- |
| referrer           |      |           | &#10003;      |
| method             |      | &#10003;  |               |
| bytes_out          |      | &#10003;  |               |
| bytes_in           |      | &#10003;  |               |
| mime               |      | &#10003;  |               |
| action             |      |           | &#10003;      |
| category           |      | &#10003;  |               |
| user_agent         |      |           | &#10003;      |
| http_response_code |      | &#10003;  |               |