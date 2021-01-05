# AZ-303 Session 1 Labs

## [Microsoft Azure Well-Architected Framework](https://docs.microsoft.com/en-us/azure/architecture/framework/)

* Cost Optimization
  * Build-Measure-Learn
  * Develop the optimal cost model
  * Budgets and Alerts
  * Advisor
* Operational Excellence
  * Monitoring and Diagnostics
* Performance Efficiency
  * Vertical and horizontal scaling
  * Redundancy (CDN)
  * Identify and resolve bottlenecks
* Reliability
  * High availability
  * Data replication
  * Fault handling
* Security
  * Full application lifecycle
  * Identity management
  * RBAC
  * Application security
    * Azure Defender
  * Data sovereignty & encryption

## Implement and Monitor Azure infrastructure

### Identity

  * Licensing
    * SKU differences
  * Custom domains
  * Cost Management
  * User security
    * SSPR
    * MFA
      * Conditional Access
      * Azure AD IdP
      * Azure AD PIM
  * Hybrid identity
    * Synchronization options
    * Synch Rules Editor
    * Password writeback
    * Azure AD Connect Health

### Storage accounts

  * Blob vs GPv2
  * Services
    * Blob
    * File
  * Advanced Threat Protection (ATP)
  * Authentication and authorization
    * Azure AD
    * Keys
    * SAS
  * Availability
    * Replication
    * Failover

* Service Bus
  * duplicate detection
  * Message ordering

### Virtual machines

  * Templates
    * DependsOn
    * Count/looping
    * ExtensionProfile
  * Dedicated host
    * Reservations
  * High availability
    * SLA percentages
    * Availability zones/sets
    * Scale sets
  * Storage
    * Performance stats / SLAs
    * Azure Disk Encryption
  * Scale set scaling rules
  * Templates
    * Library
    * DependsOn
  * Config management
    * Extensions
    * Automation runbooks


### Monitoring

  * Monitor health, availability, performance
    * Scopes
      * Azure Status
      * Azure Service Health
      * Azure Resource Health
    * Azure Advisor
      * Cost suggestions
    * Azure Monitor
      * Insights
    * Log Analytics (no queries)
    * Alerts and Action Groups
      * Automation Runbooks
