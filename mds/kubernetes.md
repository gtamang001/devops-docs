Container Orchestration Platforms, Borg for google has transformed into Kubernetes now. 
Kubernetes features 
- Multi-host container scheduling done by kube-scheduler. It checks resources,quality of service, policies, and user specifications before scheduling.
- Scalability and Availability upto 5000 nodes clusters, 150000 total pods , 100 pods per node, Pods can be horizontally scalled via API 
- Flexibility and Modularization, have Plug and play architecture, Extend architecture when needed, Add-ons: network drivers, service discovery, container runtime, visualization, and command
- Persistence storage, pods have feature of volumes for data storage
- Logging and Monitoring, Application monitoring built in such as TCP, HTTP, or container execution health check, Node Health check and failures monitored by node controller 
- Kubernetes status measured by prometheus etc 
- Secrets Management for single namespace 
- Community [best community and documentation available for kubernetes]

Market Competiton: 
- Kubernetes, 
- Mesos 
- Rancher
- EC2 container service 
- 

### Architecture 
Master Node : Is responsible for overall management of Kubernetes Clusters. Its got three components, API server, Scheduler and Controller Manager 