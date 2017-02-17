
EMQ Retainer
============

Configuration
-------------

etc/emq_retainer.conf:

```
## disc: disc_copies, ram: ram_copies
## Notice: retainer's storage_type on each node in a cluster must be the same!
retainer.storage_type = disc

## Max number of retained messages
retainer.max_message_num = 1000000

## Max Payload Size of retained message
retainer.max_payload_size = 64KB

## Expiry interval. Never expired if 0
## h - hour
## m - minute
## s - second
retainer.expiry_interval = 0
```

License
-------

Apache License Version 2.0

Author
------

Feng at emqtt.io

