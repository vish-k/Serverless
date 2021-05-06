# Serverless

## Look Ma, no servers!

<pre>
wireless    === no wires
speechless  === no speech  
headless    === no head/UI  
endless     === no end  
serverless  === no servers? </pre> 

Not really! Sorry, but serverless still has servers... then why is it called serverless? Well, there are two hard things in computer science -
1. Naming things
2. Cache Invalidation
3. Off by one :wink:

## Serverless === someone else manages the server
Exactly! serverless doesn't mean no server but someone else is responsible for managing server. "Isn't that cloud/IaaS/PaaS?" you may ask... there are subtle differneces. 

To run an application, we generally need
1. application code (java / node.js / .net core etc. code/binaries)
2. app scaling
3. code platform (jre / node /.net framework etc)
4. OS (linux/windows etc)
5. Virtualization platform (VM/container orchestration)
6. Server (on-prem/Cloud)
7. Networking & Security (physical/application)
8. Data Center

### IaaS
With IaaS the responsibilities get divided like - 
| App Owner           | Cloud Provider  |
| --------------------|-------------| 
| app code            |  |
| app scaling | |
| app platform     |       |
| VM |       |
|     | Networking |
|    | Data Center|

### PaaS
With PaaS the responsibilities get divided like - 
| App Owner           | Cloud Provider  |
| --------------------|-------------| 
| app code            |  |
| app scaling | |
| | app platform     |
| | VM |
|     | Networking |
|    | Data Center|

### FaaS
With FaaS (Function as a Service) the responsibilities get divided like - 
| App Owner           | Cloud Provider  |
| --------------------|-------------| 
| app code            |  |
| | app scaling |
| | app platform     |
| | VM |
|     | Networking |
|    | Data Center|

So with PaaS & FaaS, the cloud provider is responsible for managing the servers so it's serverless.

## Serverless Landscape
### Compute
### Storage
### Integration
### Kubernetes based FaaS

## Getting Started
