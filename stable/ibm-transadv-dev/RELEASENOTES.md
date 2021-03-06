
# What’s new in Chart Version 1.7.0
With Transformation Advisor on IBM Cloud Private 2.1.0.1+, the following new features are available:
### WORKSPACE/COLLECTION NAME CHANGE ON UPGRADE
 - We now prevent the user of certain characters for workspace and collection names
 - Special characters in the names of workspace/collections will be replaced with underscores
 - Workspace/collections with special characters and no recommendations can no longer be used
### JBoss and WebLogic Analysis
 - We now support analysis of JBoss and WebLogic applications and systems for migration!
### Migrate to IBM Kubernetes Service
 - Workspace/collections with special characters and no recommendations can no longer be used
### Usability Enhancements
 - Brand new Data Collector CLI experience including progress and time remaining
 - Brand new Data Collector download experience supporting JBoss and WebLogic
 - Improved Deploy button experience with overwrite options
 ### Data Collector Enhancements
 - Faster generation and download of the Data Collector
 - We have fixed many minor defects around the use of the Data Collector for many different platforms

# Fixes
* Fixed Nullpointer exception thrown by data collector for certain WAS Network Deployment configurations
* Fixed Sorting of the complexity column 
* Fixed bread crumb in migration steps page

# Prerequisites
* IBM Cloud Private version 2.1.0.1+

# Version History
| Chart | Date | ICP Required | Image(s) Supported | Breaking Changes | Details |
| ----- | ---- | ------------ | ------------------ | ---------------- | ------- | 
| 1.7.0 | Aug 22, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.7.0 ibmcom/transformation-advisor-server:1.7.0 ibmcom/transformation-advisor-ui:1.7.0 | None | Migrate JBoss and WebLogic |
| 1.6.0 | Jul 02, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.6.0 ibmcom/transformation-advisor-server:1.6.0 ibmcom/transformation-advisor-ui:1.6.0 | None | Add authentication         |
| 1.5.1 | Jun 05, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.5.1 ibmcom/transformation-advisor-server:1.5.1 ibmcom/transformation-advisor-ui:1.5.1 | None | Patch for new Micro Climate|
| 1.5.0 | May 21, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.5.0 ibmcom/transformation-advisor-server:1.5.0 ibmcom/transformation-advisor-ui:1.5.0 | None | Automate migration         |
| 1.4.0 | Mar 13, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.4.0 ibmcom/transformation-advisor-server:1.4.0 ibmcom/transformation-advisor-ui:1.4.0 | None | Add deployment artifacts   |
| 1.3.0 | Feb 07, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.3.0 ibmcom/transformation-advisor-server:1.3.0 ibmcom/transformation-advisor-ui:1.3.0 | None | Configurable dev costs     |
| 1.2.0 | Jan 11, 2018| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.2.0 ibmcom/transformation-advisor-server:1.2.0 ibmcom/transformation-advisor-ui:1.2.0 | None | Helper migration artifacts |
| 1.1.0 | Nov 28, 2017| >=2.1.0.1 | ibmcom/transformation-advisor-db:1.1.0 ibmcom/transformation-advisor-server:1.1.0 ibmcom/transformation-advisor-ui:1.1.0 | None | DC for multiple OSs        |
| 1.0.0 | Oct 24, 2017| >=2.1.0.1 | klaemo/couchdb:2.0.0 ibmcom/icp-transformation-advisor-dc:1.1.0 ibmcom/icp-transformation-advisor-ui:1.1.0               | None | Initial catalog entry      |
