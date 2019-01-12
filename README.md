Lab.Cloud.Azure
====
Microsoft Azure Resources


### References
* https://azure.microsoft.com/en-us/status/
* Azure products available by region
  * https://azure.microsoft.com/en-us/global-infrastructure/services/

  
### Documentation
* https://docs.microsoft.com/en-us/azure/
* https://azure.microsoft.com/en-us/campaigns/developer-guide/
* https://docs.microsoft.com/en-us/azure/
* Hybrid Connectivity Gateway
  * https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-gateway-install
  * https://docs.microsoft.com/en-us/azure/logic-apps/logic-apps-gateway-install#gateway-cloud-service

  
### Cloud Services
* https://docs.microsoft.com/en-us/azure/cloud-services/
  * https://docs.microsoft.com/en-us/azure/cloud-services/cloud-services-choose-me
* Training Vidoes 
  * https://azure.microsoft.com/en-us/resources/videos/index/?services=cloud-services
* .NET
  * https://docs.microsoft.com/en-us/azure/cloud-services/cloud-services-dotnet-get-started
* REST APIs
  * https://docs.microsoft.com/en-us/rest/api/compute/cloudservices/
  
  
  
### Azure Container Registry (ACR)
* https://azure.microsoft.com/en-us/services/container-registry/
  * "Azure Container Registry allows you to store images for all types of container deployments including DC/OS, Docker Swarm, Kubernetes, and Azure services such as App Service, Batch, Service Fabric, and others. Your DevOps team can manage the configuration of apps isolated from the configuration of the hosting environment."
  * "You don’t have to learn new APIs or commands. Because Azure Container Registry is compatible with the open-source Docker Registry v2, you can use the same open-source Docker CLI tools you already know and the skills you have to efficiently interact with the registry."
* https://docs.microsoft.com/en-us/azure/container-registry/
* https://azure.microsoft.com/en-us/pricing/details/container-registry/
  * "Azure Container Registry provides storage of private Docker container images, enabling fast, scalable retrieval, and network-close deployment of container workloads on Azure. Additional capabilities include geo-replication, image signing with Docker Content Trust, Helm Chart Repositories and Task base compute for building, testing, patching container workloads."
* Github Resources
  * https://github.com/Azure/acr
    * https://github.com/Azure/acr/tree/master/docs
	  * https://github.com/Azure/acr/blob/master/docs/acr-roadmap.md

	
  
### Azure Resource Manager (ARM)
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/
* https://docs.microsoft.com/en-us/azure/azure-resource-manager/resource-group-overview


### Azure Kubernetes Service (AKS)
* https://docs.microsoft.com/en-us/azure/aks/
* https://azure.microsoft.com/en-us/services/kubernetes-service/
* https://azure.microsoft.com/en-us/updates/?product=kubernetes-service
* https://github.com/Azure/AKS
   https://github.com/Azure/AKS/blob/master/previews.md
* https://github.com/Azure/aks-engine/
  * https://github.com/Azure/aks-engine/blob/master/docs/README.md
  * https://github.com/Azure/aks-engine/blob/master/docs/tutorials/README.md
  * https://github.com/Azure/aks-engine/blob/master/docs/topics/README.md
  
  
  
### Azure Templates
* https://azure.microsoft.com/en-us/resources/templates/
  * https://azure.microsoft.com/en-us/resources/templates/?term=docker&pageNumber=1 
    * https://azure.microsoft.com/en-us/resources/templates/docker-kibana-elasticsearch/
	* https://azure.microsoft.com/en-us/resources/templates/docker-swarm-cluster/
	* https://azure.microsoft.com/en-us/resources/templates/docker-rancher/
	* https://azure.microsoft.com/en-us/resources/templates/docker-neo4j/
	* https://azure.microsoft.com/en-us/resources/templates/docker-parse/
	* https://azure.microsoft.com/en-us/resources/templates/docker-wordpress-mysql/
	* https://azure.microsoft.com/en-us/resources/templates/docker-simple-on-ubuntu/
	* https://azure.microsoft.com/en-us/resources/templates/301-jenkins-aks-zero-downtime-deployment/
	* https://azure.microsoft.com/en-us/resources/templates/jenkins-cicd-container/

  
### Azure Container Instances
* https://docs.microsoft.com/en-us/azure/container-instances/
  * "Certain features of Azure Container Instances are in preview, and some limitations apply."
  * https://docs.microsoft.com/en-us/rest/api/container-instances/listcapabilities/listcapabilities
    * Example: ```GET https://management.azure.com/subscriptions/{subscriptionId}/providers/Microsoft.ContainerInstance/locations/{location}/capabilities?api-version=2018-10-01```
  * https://github.com/Azure/acs-engine
    * Azure Container Service Engine - provision and deploy container orchestrators on Azure: Kubernetes, DC/OS, and Docker Swarm. 
	* ```"This codebase has been deprecated in favor of aks-engine, the natural evolution from acs-engine"```
  * https://github.com/Azure/aks-engine
    * AKS-Engine: Units of Kubernetes on Azure! 
	* "AKS-Engine provides convenient tooling to quickly bootstrap Kubernetes clusters on Azure. By leveraging ARM (Azure Resource Manager), AKS-Engine helps you create, destroy and maintain clusters provisioned with basic IaaS resources in Azure. AKS-Engine is also the library used by AKS for performing these operations to provide managed service implementations."
	* https://github.com/Azure/aks-engine/blob/master/docs/README.md
* Docker.com Resources
  * https://hub.docker.com/editions/enterprise/docker-ee-azure?tab=description
  * https://docs.docker.com/v17.09/docker-for-azure/
	* https://docs.docker.com/v17.09/docker-for-azure/faqs/
  * https://hub.docker.com/editions/enterprise/docker-ee-azure?tab=description
  * https://docs.docker.com/v17.09/docker-for-azure/faqs/
	* "Docker for Azure should work with all supported Azure Marketplace regions."
	* "All regions can be found here: Microsoft Azure Regions. An excerpt of the above regions to use when you create your service principal are:"
	  * "usgovvirginia"
	  * "usgoviowa"
  * [Microsoft Azure Channel, How to run an app inside a container image with Docker | Azure Tips and Tricks](https://www.youtube.com/watch?v=lpr2tO-FCEw)
* Visual Studio 2017 Support for Docker
  * [Using Visual Studio Tools for Docker (Visual Studio on Windows)](https://docs.microsoft.com/en-us/dotnet/standard/containerized-lifecycle-architecture/design-develop-containerized-apps/visual-studio-tools-for-docker?toc=/visualstudio/docker/toc.json&bc=/visualstudio/docker/breadcrumb/toc.json&view=vs-2017)
    * "The Visual Studio Tools for Docker development workflow is similar to the workflow when using Visual Studio Code and Docker CLI. In fact, it's based on the same Docker CLI, but it's easier to get started, simplifies the process, and provides greater productivity for the build, run, and compose tasks. Execute and debug your containers via simple actions like F5 and Ctrl+F5. With the optional container orchestration support, in addition to being able to run and debug a single container, you can run and debug a group of containers (a whole solution) at the same time."
	* "There are two levels of Docker support you can add to a project. In .NET Core web app projects, you can just add a Dockerfile file to the project by enabling Docker support. The next level is container orchestration support, which adds a Dockerfile to the project (if it doesn't already exist) and a docker-compose.yml file at the solution level. Container orchestration support, via Docker Compose, is added by default in Visual Studio 2017 versions 15.7 or earlier. Container orchestration support is an opt-in feature in Visual Studio 2017 versions 15.8 or later, in which case Docker Compose and Service Fabric are supported."
  * [Debugging apps in a local Docker container](https://docs.microsoft.com/en-us/visualstudio/docker/vs-azure-tools-docker-edit-and-refresh?view=vs-2017)
  
### Virtual Machines
* https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sizes
* https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/
  * https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview

  
### Azure Batch
* https://docs.microsoft.com/en-us/azure/batch/
  * https://docs.microsoft.com/en-us/azure/batch/batch-technical-overview

  
  
### Azure Stack (for on-prem deployments)
* https://azure.microsoft.com/en-us/overview/azure-stack/
  * https://azure.microsoft.com/en-us/resources/videos/microsoft-azure-stack-azure-services-on-premises/


  
Interesting Azure News Articles
====
* https://azure.microsoft.com/en-us/blog/new-lower-azure-pricing/
* https://azure.microsoft.com/en-us/blog/announcing-general-availability-of-vm-storage-and-network-azure-cli-2-0/


