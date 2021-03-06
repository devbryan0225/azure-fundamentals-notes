# Modules
- Introduction to Azure fundamentals
- Explore Azure database and analytics services
- Explore Azure compute services
- Explore Azure storage services
- Explore Azure networking services

## Explore Azure database and analytics services
- explore > assess > migrate > cutover > optimize

## Cosmos
- gremlin API

## compute services

### VM scale sets
- deploy and manage identical VMs

### why VM
- control over OS
- run custom software
- run custom host config

### when VM
- during test and development
- running apps in the cloud
- extending datacenter to the cloud
- disaster recovery

### azure container vs azure kubernetes
- kubernetes to manage containers, orchestration

### azure functions
- stateless default or stateful via Durable Functions

### azure logic app
- web based even trigger

## Azure Storage Services
- create storage account first

### azure files
- share anywhere with URL

### blob
- hot, cool, archive access tier
- archive set at blob level when upload
- cost to rehydrate archive files

## Azure Networking Services
- between azure resources : virtual networks, service endpoints
- with on premise : point-to-site vpn, site-to-site vpn, expressroute
- route network traffic : route tables, border gateway protocol
- filter network traffic : network security group, network virtual appliances

### VPN Gateway
- policy based and route based
- dynamic routing uses Border Gateway Protocol

## ExpressRoute
- private connectivity but no encryption
- allows : redundant connectivity, consistent network throughput, access to ms cloud services
- models : any-to-any, point-to-point, cloud colocation

## link virtual networks
- peering
