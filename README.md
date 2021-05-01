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
Exactly! serverless doesn't mean no server but someone else is responsible for managing server. "Isn't that cloud/IaaS/PaaS?" you may ask... there are subtle differneces. To run an application, we generally need
1. application code (java / node.js / .net core etc. code/binaries)
2. code platform (jre / node /.net framework etc)
3. OS (linux/windows etc)
4. Virtualization platform (VM/container orchestration)
5. Server (on-prem/Cloud)
6. Networking
7. Security (physical/application)
