# AZ-303 Session 2 Labs

## Sweep Up the Shavings

  * VS Code tutorial
  * TLS cert with blob service
  * microsoft.directory/applications/createAsOwner
  * ARM template - SAS Token

## Implement Management and Security Solutions

### Workload migration and management

  * Azure Migrate
    * Virtual machines
    * Supported OS versions, memory, disk limits
  * Azure VMs
    * Backup / recovery
    * Disaster recovery
  * Azure Update Management

### Network load balancing & security

  * VNets
    * Security
      * NSGs
        * ASGs
    * Service/private endpoints* Peering
      * Connectivity paths
    * Load balancing
      * Azure Load Balancer
      * Azure Application Gateway
      * Azure Front Door
      * Azure Traffic Manager
    * Azure Firewall
      * Firewall Manager

### Governance

  * Management scopes
  * RBAC
    * Custom roles
      * JSON
    * Managed identity (169.254)
  * Azure Policy
  * Azure Blueprints

## Application Solution Architecture

### Application infrastructure and security

  * App Service
    * ASPs
      * Pricing plans and limits
    * Certificate mutual auth
    * Managed Identities
    * Deployment slots
  * Serverless
    * Logic Apps
    * Functions
  * Containers
    * DOCKERFILE syntax
    * Build image, deploy to ACR and ACI
    * AKS
      * kubectl apply manifest.yaml

## Data Platforms

### SQL databases

  * Azure SQL Database
    * Managed Instance
  * High availability options
  * Publish process
  * Pools and moving DBs
  * Basic SQL CREATE TABLE order

  * Azure Cosmos DB
    * Choose an API
    * Configure replication
    * SQL API
      * Partition key
        * New PK, new container
      * SQL syntax
      * EnableCrossPartitionQuery