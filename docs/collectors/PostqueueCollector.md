<!--This file was generated from the python source
Please edit the source to make changes
-->
PostqueueCollector
=====

Collect the emails in the postfix queue

#### Dependencies

 * subprocess


#### Options

Setting | Default | Description | Type
--------|---------|-------------|-----
bin | /usr/bin/postqueue | The path to the postqueue binary | str
byte_unit | byte | Default numeric output(s) | str
enabled | False | Enable collecting these metrics | bool
measure_collector_time | False | Collect the collector run time in ms | bool
metrics_blacklist | None | Regex to match metrics to block. Mutually exclusive with metrics_whitelist | NoneType
metrics_whitelist | None | Regex to match metrics to transmit. Mutually exclusive with metrics_blacklist | NoneType
sudo_cmd | /usr/bin/sudo | Path to sudo | str
use_sudo | False | Use sudo? | bool

#### Example Output

```
servers.hostname.postqueue.count 3
```

