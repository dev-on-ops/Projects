# Projects
Place to track personal projects and status

# Infrastruture
0. Lab resources
- lab host
- gateway server
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
2. Support services DNS
- Deploy DNS services
  * deploy ha dns via powerdns - 1 master, 1 replica
  * deploy dns recursors - 2 node
  * deploy DNS Load balancers - 2 node
  * Programmatic update of records
3. Support services Auth
- Deploy Auth services
  * Active Directory
4. Support services Secrets and PKI
- Deploy Offline Root and Intermediate
  * CRL server
  * offline root
  * Online Intermediate
- Deploy Hashicorp Vault cluster
  * Vault for Unseal - 1 node
  * Vault for secrets and pki - 3 node
  * Ha Proxy for load balancing - 2 node
5. Support services Logging
- Deploy ELK Clusters
  * Ha deployment with load balancing - 4 node
6. Support services Metrics
- Deploy Graphite Clusters
  * load balanced and routed - 2 node
7. Support Services Monitoring
- Deploy Zabbix instance
8. Support services Managed Server
- Deploy managed server
  * DNS registered at provisioning
  * Metrics sent to graphite
  * logs sent to ELK
  * Bound to domain in appropiate OU
  * PKI Trust chain installed
  * Monitored for basic health checks
