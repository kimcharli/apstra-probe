# Probes
The probes are blueprint specific.

## Start from the Analytics > Probes page
![Probes](./sources/probes.png)

## Create Probe from 'New Probe'
![Create a Probe](./sources/create-probe.png)

## Name the probe
![Name the probe and Add Processsor](./sources/probe-name.png)

## Add a Processor
- Probe Type: Extensible Service Data Collector
- Processor Name: ddos-vxlan
- Output Stage Name: ddos-vxlqn
![Add processor](./sources/probe-add-processor.png)

## Update Graph Query
- Predefined Query: DC - All leafs and access switches
![Update Graph Query](./sources/probe-graph-query.png)

## Update the Processor
- Query Group By: system (optional)
- System ID: system.system_id (depends on the query)
- Service Name: ddos-vxlan (the service defined earlier)
![Service Name](./sources/probe-service-name.png)

## Data Type
- Data Type: Dynamic Number
![Dynamic Number](./sources/probe-dynamic-number.png)

## Inspect Output Stage ddos vxlan
![stage](./sources/probe-output.png)


## Add Processor - Range
![range](./sources/probe-processor-range.png)


## Set Range
![set range](./sources/probe-range.png)

## Inspect the Range Stage
![range state](./sources/probe-range-stage.png)

