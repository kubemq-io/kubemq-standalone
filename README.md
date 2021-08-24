# What is KubeMQ Standalone?

KubeMQ Standalone is the single server commercial version of KubeMQ, the Kubernetes native message broker.
[More about KubeMQ](https://kubemq.io/)

# Installation

Every installation method requires a KubeMQ key.
Please [register](https://account.kubemq.io/login/register) to obtain your KubeMQ key.

## Docker

Pull and run KubeMQ standalone docker container:

``` bash  
docker run -d -p 8080:8080 -p 50000:50000 -p 9090:9090 -e KEY={{yourkey}} kubemq/kubemq-stanalone:latest  
```  

## Binaries
KubeMQ standalone binaries are available for Edge locations and for local development.

1. Download the latest version of KubeMQ Standalone from [Releases](https://github.com/kubemq-io/kubemq-standalone/releases)
2. Unpack the downloaded archive
3. Run ```kubemq -k {{your key}}``` (A key is needed for the first time only)

# KubeMQ Connectors

|Name | Description | Github | 
|--|--|--| 
| **KubeMQ Targets** | Connect KubeMQ Message Broker with external systems and cloud services |[KubeMQ Targets](https://github.com/kubemq-hub/kubemq-targets)|
| **KubeMQ Sources** | Connects external systems and cloud services with KubeMQ message queue broker |[KubeMQ Sources](https://github.com/kubemq-hub/kubemq-sources)|
| **KubeMQ Bridges** | bridge, replicate, aggregate, and transform messages between KubeMQ |[KubeMQ Bridges](https://github.com/kubemq-hub/kubemq-bridges)|



# KubeMQ SDKs

KubeMQ SDKs support list:

| SDK | Github   |  
|:----|:---|  
| C#    |  https://github.com/kubemq-io/kubemq-CSharp  |  
| Java    | https://github.com/kubemq-io/kubemq-Java |  
| Python    |  https://github.com/kubemq-io/kubemq-Python  |  
| Node    |  https://github.com/kubemq-io/kubemq-js |  
| Go    | https://github.com/kubemq-io/kubemq-go |  
| REST    |  https://postman.kubemq.io/ |  

## KubeMQ Cookbooks

| SDK | Github   |  
|:----|:---|  
| C#    |  https://github.com/kubemq-io/csharp-sdk-cookbook  |  
| Java    | https://github.com/kubemq-io/java-sdk-cookbook |  
| Python    |  https://github.com/kubemq-io/python-sdk-cookbook |  
| Node    |  https://github.com/kubemq-io/node-sdk-cookbook |  
| Go    | https://github.com/kubemq-io/go-sdk-cookbook|  

## Documatation

Visit our [Extensive KubeMQ Documentation](https://docs.kubemq.io/).

## Support

You can reach us at:

- [**Email**](mailto:support@kubemq.io)
- [**Slack**](https://kubemq.slack.com)
  - [Invitation](https://join.slack.com/t/kubemq/shared_invite/enQtNDk3NjE1Mjg1MDMwLThjMGFmYjU1NTVhZWRjZTRjYTIxM2E5MjA5ZDFkMWUyODI3YTlkOWY2MmYzNGIwZjY3OThlMzYxYjYwMTVmYWM)
- [**Open an issue**](https://github.com/kubemq-io/kubemq-standalone/issues)
