# EXAM-900 : FUNDAMENTALS

## CONCEPTS & SERVICES

### INTRODUCTION

What is Azure ? -> A private and public cloud computing platform (on premises and at the edge) with a set of services ready to use to build, manage and deploy applications.

It includes services on internet: storage, dbs, networking, software, analytics and AI.

Portal: A web-based unified console that provides an alternative to CLI tools. Used for custom fit workflow, projects and styles. Manage subscription. It updates continuously and there is no downtime for maintenance. It is resilient to individual datacenter failures and avoird network slowdowns.
* Build, manage and monitor
* Create custom dashboards
* Configure accesibility options

![screenshot](https://github.com/robnob/EXAM-900/blob/main/01How_does_azure_work.JPG)

<ins>Capabilities (Categories) :</ins>
1. Compute Services: VM, containers and serverless computing, including micro-services for performing calculations, executing logics and running applications.
2. Cloud Storage : disks attached to VM as well as wells as vault shares and databases.
3. Networking : Linking compute resources and providing access to applications is the key function of Azure networking.
4. App Hosting : for running applications in Windows or Linux.
5. Artificial Intelligence : ML and conginitve services, search and analyze existing data to forecast future behaviours, outputs and trends.
6. Internet of things : manage and integration of sensors and devices, to control and monitor all your assets through a customisable dashboard.
7. Integration : logic apps and service bus connect applications and services, it allow workflows to orchestrate business processes.
8. Security : integrated in every aspect of Azure, Identity Management control, global security intelligence monitoring.

<strong> Azure Marketplace </strong>

It connects Azure users to microsoft vendor partners and startups. Applications and services:
* Find
* Try
* Purchase
* Provision

Solutions catalogue categories:

1. VM
2. DB
3. Application Build
4. Blockchain
5. Threat Detection
6. Developement Tools
7. Deployment Software

   [List of Azure Services](https://github.com/robnob/EXAM-900/blob/main/List%20of%20Azure%20services%20_%20Coursera.pdf)





### FUNDAMENTAL CONCEPTS & ARCHITECTURAL COMPONENTS

#### Subscriptions, Management groups, ARM, resources and accounts 

Account Vs Subscriptions:

![screenshot](https://github.com/robnob/EXAM-900/blob/main/02Accounts_Vs_Subscriptions.JPG)

An <strong> Azure resource </strong> is an item that is available through Azure: VMs, storage accounts, webex, Azure application gateway instances, Dbs and VNs are some exemples of resources.
   * They must be organised into containers, the <strong> Resource Group </strong>
   * A ressource cannot be a memeber of more than one resource group.
   * Resource groups cannot be nested.
   * It is better to group resources by life cycle in non-production environments.
   * Apply RBAC (Role-based access control)permissions to ease administration and limit access.
 
The <strong> Azure resource Manager (ARM) </strong>: the deployment and management service for Azure, 
   * It allows creating, updating and deleting a resource.
   * Features like : access control, locks and tags to secure and organize your resources after deployment.
   * It get the requests from any Azure tool API and from any other SDK.
   * It manages resources with templates (a json file) rather than with scripts
   * Deploy resources within a group and not individually
   * Redeploy solutions
   * Define dependencies
   * Apply RBACs
   * Apply tags
   * Clarify the organization billing

![screenshot](https://github.com/robnob/EXAM-900/blob/main/05ARM.JPG)
 
<strong> Azure Management Groups </strong> provides a level of scope above subscriptions, it is a container where the governance conditions are applied:
  * The subscriptions attached to the group automatically inherit these conditions,
  * All the subscriptions in the same management group should rely in the same trust ID tenant.
  * Up to 10.000 groups can be created.
  * Up to 6 levels of depth (excluding the root and the subscriptions levels)
  * One parent per group, but 1 to many children.
  * Single hierarchy.

An <strong> Azure Subscription </strong>, a logical unit of Azure services, provides you with:
  1. Authenticated and authorised access to Azure products and services and
  2. It allows you to provision resources.
 
   There are two types of subscription boundaries:
  1. Billing: it determines how the Azure account, it is possible to create multiple subscriptions for each type of billing requirements. The repports and invoices are generated separately for each subscription.
  2. Access control: access management policies at the subscription level, it is possible to create different subscriptions to reflect different organizations's structures.
 
The creation of subscriptions could follow the needs of reflecting:
   * All possible environments (Production, pre-production, etc.)
   * Organizational structures
   * Billing

<strong> Azure account </strong> is an identity in the Azure Active directory or in another directory in which the Azure ID trusts.

#### Regions and availability zones

  Region: a geographical area in the planet:
  *   It contains one or more data centers
  *   It is needed to deploy resources:
        Some services (Vms sizes and storage types) are available just in some regions
        Some services do not need to select a region, like AD, DNS and traffic manager, they are global.
        it is needed to select one when provisionzing resources, but some of them are available globally.
        
  Availability Zones are different physical data centers within a region with independent:
   *   Cooling
   *   Power
   *   Networking

   There are two categories of availability zones:
   1. <strong> Zonal services: </strong> you pin the resource to a specific zone, i.e. VMs, managed disks and IP addresses.
   2. <strong> Zone redundant services: </strong> The platform replicates automatically across zone, I.e. storage, SQL DB.

Region Pairs

Regions in the same geography that are paired to contour regional disasters

#### Benefits of Cloud Environment Vs a physical one

1. Availability
2. Scalability
3. Elasticity
4. GeoDistribution
5. Agility
6. Disaster Recovery

#### Two types of expenditures

1. CAPEX: Capital expenditures (the value reduces over time)
2. OPEX: Operational expenditures (build at the moment of use)

<strong> IaaS, Vs. PaaS Vs. SaaS: </strong>

![screenshot](https://github.com/robnob/EXAM-900/blob/main/03Saas_Paas_Iaas.JPG)

<strong> Client Vs Provider: </strong>

![screenshot](https://github.com/robnob/EXAM-900/blob/main/04ClientVsProvider.JPG)

#### Types de Deploiement

1. Hybrid
2. Public
3. Private

### DB, ANALYTICS AND COMPUTE SERVICES

#### COSMOS DB

#### SQL DATABASE 

#### MANAGE INSTANCES

#### DB FOR 

##### MySQL

##### PostGreSQL

### BIG DATA AND SERVICES

### VIRTUALIZATION SERVICES

### STORAGE OPTIONS A NETWORK SERVICES

#### BLOB

#### DISK

#### FILES

#### BLOB ACCESS TIERS

### NETWORKING RESSOURCES

#### VIRTUAL NETWORK

#### VPN GETWAY

#### EXPRESS RIGHT (Communication Tunnels)

## OTHER PATHWAYS

  * EXAM-900 : Fundamentals. (40 -50 questions)
    <pre> 
      <br> CLOUD CONCEPTS (20-25%) </br>
      <br> IDENTITY, GOVERNANCE, PRIVACY AND COMPLIANCE FEATURES (20-25%) </br>
      <br> CORE SERVICES (15-20%) </br> 
      <br> CORE SOLUTIONS (10-15%) </br>
      <br> SECURITY FEATURES (10-15%) </br>
      <br> COST MANAGEMENT AND SERVICE LEVEL AGREEMENTS(SLA) (10-15%) </br>
    </pre>
    https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/?practice-assessment-type=certification
    
  * EXAM-904 : administrator

  * EXAM-204 : developper 

  * EXAM-??? : DevOps

### LEVELS

    * Fundamental
    * Associate (> 2 years)
    * Expert (> 5 years)





