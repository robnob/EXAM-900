# FUNDAMENTALS
## CLOUD CONCEPTS

<ins> Cloud Computing </ins>: is the delivery of computing services over the internet, including:
1. VMs (Compute power: the amount of processing that can be done)
2. Storage (Volume of data trhat can be stored)
3. DBs
4. Networking
5. IoT
6. ML
7. AI

### Azure Models

#### Shared responsibility model
<ins> IaaS </ins>:  Infrastructure as a Service, it places the most responsibility on the consumer, with the cloud provider being responsible for the basics of physical security, power, and connectivity

<ins>PaaS </ins>:  Platform as a Service

<ins> SaaS </ins>:  Software as a Service, it places most of the responsibility with the cloud provider

![Screenshot](https://github.com/robnob/EXAM-900/blob/main/06SRM.JPG)

#### Cloud Models

1. Public: The general public availability is a key difference between public and private clouds
2. Private: It’s a cloud that’s used by a single entity.
3. Hybrid: It is used to allow a private cloud to surge for increased, temporary demand by deploying public cloud resources and also to provide an extra layer of security
4. Multi-Cloud: It uses multiple public cloud providers.

<ins>Azure Arc </ins> : A set of technologies that help you to manage your cloud environment on any of the described models.

#### Consumption Models

CapEx: it is a one-time up-front expenditure.
OpEx: It is an expenditure ein services or products over time.

Cloud computing falls under OpEx, beacause the client pays for its use. It is the pay-as-you-go pricing model.

## ARCHITECTURE AND SERVICES

### Benefits

#### Availability and Scalability

* Availability: the resources are available regardless disruptions or any other events, also known as Up time and it is measurable in % in the SLAs.
  Examples:
  * 99% -> 1,68hrs downtime / week or 7,2hrs /month
  * 99,9 % -> 10min / week or 43,2 min / month
* Scalability: The resources can increase or decrease (manually or automatically) depending on the demand. There two types:
  1. Vertical: focus on the capabilities of ressources (more or less  CPUs ou RAM)
  2. Horizontal: focus on the number of ressources (more, "scaling out"  or less "scaling in" VMs or containers)
 
#### Reliability and Predicatbility

* Reliability: the ability of a system to recover of failure.
* Predicatbility:
  - Perfomance: focus on predicting the resources needed to deliver a positive experience to the customer, supported by, among other concepts:  autoscaling, load balancing and high availability.
  - Cost: Forecast the cost of the cloud spend, track real time use, monitor if the ressources are used in an efficient way and apply data analytics.
 
#### Governance and Security

* Governance: a set of templates help in maintaining industrie standards and government requirements. Flags can be used to easily recognize those service that are out of compliance
* Security: Azure is prepared to apply DDOs and depending on the chosen cloud model (IaaS, PaaS, SaaS) the security over the management of the resources changed from client to the clous provider.

#### Manageability

* Of the cloud: (managing your cloud resources)
  - Automatic scaling
  - Use of templates for deploying
  - Monitor of health of resources
  - Alerts receiving based on configured metrics.
    
* In the cloud (how to manage the cloud environment and resources):
  - Web Portal
  - CLI
  - APIs
  - PowerShell
 
## MANAGEMENT AND GOVERNANCE

## ACRONYMS

<strong> RBAC: </strong> Role-based Access Control
<strong> SLAs: </strong>: Service level agreements
<strong> DDOs: </strong>: Distributed Deniel of Service

