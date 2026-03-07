1. 

![Image alt](https://github.com/jaack1/netology-monitoring/blob/main/screenshots/14-1.png)

2. 

100 - (avg(irate(node_cpu_seconds_total{mode="idle"}[30m])) * 100)

node_load1; node_load5; node_load15.

(node_memory_MemFree_bytes / node_memory_MemTotal_bytes) * 100

(node_filesystem_avail_bytes{device="/dev/nvme0n1p2", fstype="ext4", instance="nodeexporter:9100", job="nodeexporter", mountpoint="/"} / node_filesystem_size_bytes{device="/dev/nvme0n1p2", fstype="ext4", instance="nodeexporter:9100", job="nodeexporter", mountpoint="/"}) * 100

3. 

![Image alt](https://github.com/jaack1/netology-monitoring/blob/main/screenshots/14-3.png)

4. 

https://github.com/jaack1/netology-monitoring/blob/main/grafana/dashboard.json