# Collectors

## Create a Collector
![Collectors](./sources/collectors.png)

## 1 Associate the service
- service: ddos-vxlan (cretaed before)
![Associate the service created](./sources/collector-create.png)

## 2 Select the Platform
- OS: junos
- OS Variant: junos-qfx (and/or others)
- OS Versio: 22.2r2
![Select the Platform](./sources/collector-platform.png)

## 3 Set the command to use
- command: show ddos-protection protocols vxlan statistics
- Click Execute to get a snapshot form a switch
![Choose the command to use](./sources/collector-command.png)

## 4.1 Map the key 'fpc' to the locale
![Associate the key to output with Default Mapping View](./sources/collector-key.png)

## 4.2 Associate value to packet-arrival-rate-max
- Value Expression = int(value or 0)
![Associate the value in Advanced Mapping View](./sources/collector-value.png)