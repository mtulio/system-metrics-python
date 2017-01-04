# system-metrics-python
[WIP] Module to get system metrics using python

The idea is that we can get system metrics and show it on stdout or output file. The format could be JSON, YAML or single-line - maybe send it to external system metrics/monitoring like Librato, Grafite, Zabbix.....

Examples of metrics to get:

* OS Network connections (TCP [stablished, timewait, closed,...] UDP)
* OS total of proccess and its attributes (top mem, cpu...)
...
