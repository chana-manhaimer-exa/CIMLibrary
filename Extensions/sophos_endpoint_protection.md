sophos endpoint protection
==========================

```JSON
{"expression":"product = sophos endpoint protection",
"activity_type":{"peripheral_storage-activity":{"fields":{"src_ip":{"Status":"Default",
"core":"0",
"detection":"1",
"informational":"0"},
"bytes":{"Status":"Default",
"core":"0",
"detection":"0",
"informational":"1"},
"file_name":{"Status":"Default",
"core":"0",
"detection":"0",
"informational":"1"}}},
"alert-trigger":{"fields":{"file_path":{"Status":"Legacy",
"core":"0",
"detection":"0",
"informational":"1"},
"access":{"core":"0",
"detection":"0",
"informational":"0"},
"device_id":{"core":"0",
"detection":"0",
"informational":"0"},
"file_name":{"Status":"Legacy",
"core":"1",
"detection":"0",
"informational":"0"},
"file_dir":{"Status":"Legacy",
"core":"0",
"detection":"0",
"informational":"1"},
"src_host":{"Status":"Legacy",
"core":"1",
"detection":"1",
"informational":"0"},
"result":{"core":"0",
"detection":"0",
"informational":"0"},
"src_ip":{"Status":"Legacy",
"core":"1",
"detection":"1",
"informational":"0"},
"additional_info":{"core":"0",
"detection":"0",
"informational":"0"},
"alert_id":{"Status":"Legacy",
"core":"0",
"detection":"0",
"informational":"1"},
"dest_ip":{"Status":"Legacy",
"core":"1",
"detection":"1",
"informational":"0"},
"domain":{"core":"0",
"detection":"0",
"informational":"0"},
"dest_host":{"Status":"Legacy",
"core":"0",
"detection":"1",
"informational":"0"},
"malware_url":{"core":"0",
"detection":"0",
"informational":"0"},
"user":{"Status":"Legacy",
"core":"0",
"detection":"1",
"informational":"0"}}},
"peripheral_storage-insert":{"fields":{"src_ip":{"core":"0",
"detection":"0",
"informational":"0"}}},
"http-session":{"fields":{"malware_url":{"Status":"Default",
"core":"0",
"detection":"0",
"informational":"1"},
"src_host":{"Status":"Default",
"core":"0",
"detection":"1",
"informational":"0"}}},
"network-session":{"fields":{}}},
"fields":{"domain":{"core":"0",
"detection":"1",
"informational":"0"},
"alert_id":{"core":"0",
"detection":"0",
"informational":"1"},
"src_host":{"core":"1",
"detection":"0",
"informational":"0"},
"user":{"core":"1",
"detection":"1",
"informational":"0"},
"alert_type":{"core":"0",
"detection":"0",
"informational":"1"},
"alert_name":{"core":"0",
"detection":"0",
"informational":"1"}}}
```