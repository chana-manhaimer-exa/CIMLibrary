message-receive
===============

Description
-----------
A chat messaged was received by a user

The possible fields for this activity type will vary depending on whether the activity was a [success](#message-receivesuccess) or a [fail](#message-receivefail).

| Parameter     | Value           |
| ------------- | --------------- |
| Subject       | message         |
| Activity      | receive         |
| Activity Type | message-receive |
| Pretty Name   | Message Receive |
| Legacy Name   |                 |

message-receive:success
-----------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| dest_domain |      |           | &#10003;      |
| dest_user   |      |           | &#10003;      |

message-receive:fail
--------------------

| Field       | Core | Detection | Informational |
| ----------- | ---- | --------- | ------------- |
| dest_domain |      |           | &#10003;      |
| dest_user   |      |           | &#10003;      |