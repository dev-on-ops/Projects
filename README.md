# Projects
Place to track personal projects and status

# Infrastruture
0. Lab resources
- lab host
- dns server
- management server
- pxe boot server
- Git Repos
1. bare metal and vm provisioning 
- Deploying bare metal os via pxe
  * Windows server 2016
  * centos 7
  * ubuntu 18
- Deploy vms via api or tool
  * Windows server 2016
  * centos 7
  * ubuntu 18
2. Support services 1
- Deploy DNS services
  * deploy ha dns via powerdns - 1 master, 1 replica
- Deploy Auth services
  * Active Directory
- Deploy Hashicorp Vault cluster
  * Vault for Unseal - 1 node
  * Vault for secrets and pki - 3 node
  * Ha Proxy for load balancing - 2 node
- Deploy ELK Clusters
  * Ha deployment with load balancing - 4 node
- Deploy Graphite Clusters
  * load balanced and routed - 2 node
- Deploy managed server
  * DNS registered at provisioning
  * Metrics sent to graphite
  * logs sent to ELK
  * Bound to domain in appropiate OU
  * 
