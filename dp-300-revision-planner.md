# DP-300

## Intro

Note - this is a dump of my notes as they were when I sat the exam, I've just dumped them out of Notion, no update happened after the exam.

There isn't a DP-300 learning path as I write this, I took the detailed skills outline and used my knowledge, plus the MSDocs to fill in my gaps. I always do this before I start revising my weak spots, it becomes my revision plan. It may also be worth searching in MSLearn for SQL while there's no learning path as new content is added and removed - [Search learning for SQL](https://docs.microsoft.com/en-us/learn/browse/?term=sql) 

This is a mix of free and paid content, but mostly free, it covers labs, workshops and Microsoft Learn tasks. The section "Main resources outside of Docs" are generic learning sources, they cover one or more of the skills listed below them. Detail for what I think each skill point is referencing is then added with a direct link to something in the Docs or part of the Main resources section.

I didn't watch everything I have listed here video wise, they're listed incase I felt I needed another voice on a topic. My way of studying is to build out the environments and test them. I also used to be a DBA (a long time ago), so some parts of this will be light as I just needed a refresher. Hope it helps!

## Main resources outside of Docs

**Reading Material / Workshops**

- [https://microsoft.github.io/sqlworkshops/](https://microsoft.github.io/sqlworkshops/) - Workshops written by Microsoft Engineering, awesome content :)
- [https://azure.microsoft.com/en-gb/resources/sql-server-azure-virtual-machines/](https://azure.microsoft.com/en-gb/resources/sql-server-azure-virtual-machines/) - SQL Server on Azure VM's - free eBook by Pack
- [https://azure.microsoft.com/mediahandler/files/resourcefiles/professional-azure-sql-database-administration/Professional_Azure_SQL_Database_Administration.pdf](https://azure.microsoft.com/mediahandler/files/resourcefiles/professional-azure-sql-database-administration/Professional_Azure_SQL_Database_Administration.pdf) - Professional Azure SQL Database Administration
- [https://docs.microsoft.com/en-gb/learn/paths/work-with-relational-data-in-azure/](https://docs.microsoft.com/en-gb/learn/paths/work-with-relational-data-in-azure/)

**Video Courses**

- [https://www.pluralsight.com/courses/microsoft-azure-implementing-relational-database-solutions](https://www.pluralsight.com/courses/microsoft-azure-implementing-relational-database-solutions)
- [https://app.pluralsight.com/library/courses/introduction-azure-data-migration-service/table-of-contents](https://app.pluralsight.com/library/courses/introduction-azure-data-migration-service/table-of-contents)
- [https://app.pluralsight.com/library/courses/microsoft-azure-optimizing-data-solutions/table-of-contents](https://app.pluralsight.com/library/courses/microsoft-azure-optimizing-data-solutions/table-of-contents)
- [https://app.pluralsight.com/library/courses/microsoft-azure-configuring-encryption-data-rest/table-of-contents](https://app.pluralsight.com/library/courses/microsoft-azure-configuring-encryption-data-rest/table-of-contents)
- [https://app.pluralsight.com/library/courses/microsoft-azure-databases-access-securing/table-of-conten](https://app.pluralsight.com/library/courses/microsoft-azure-databases-access-securing/table-of-contents)ts
- [https://app.pluralsight.com/library/courses/microsoft-azure-configuring-encryption-data-rest/table-of-contents](https://app.pluralsight.com/library/courses/microsoft-azure-configuring-encryption-data-rest/table-of-contents)
- [https://app.pluralsight.com/library/courses/analyzing-sql-server-query-plans/table-of-contents](https://app.pluralsight.com/library/courses/analyzing-sql-server-query-plans/table-of-contents)
- [https://app.pluralsight.com/library/courses/azure-sql-database-diagnosing-performance-issues-dmvs/table-of-contents](https://app.pluralsight.com/library/courses/azure-sql-database-diagnosing-performance-issues-dmvs/table-of-contents)
- [https://app.pluralsight.com/library/courses/microsoft-azure-optimizing-data-solutions/table-of-contents](https://app.pluralsight.com/library/courses/microsoft-azure-optimizing-data-solutions/table-of-contents)
- [https://app.pluralsight.com/library/courses/managing-azure-sql-server-database-performance/table-of-contents](https://app.pluralsight.com/library/courses/managing-azure-sql-server-database-performance/table-of-contents)
- [https://app.pluralsight.com/library/courses/sql-server-microsoft-administering-availability-groups/table-of-contents](https://app.pluralsight.com/library/courses/sql-server-microsoft-administering-availability-groups/table-of-contents)
- [https://www.udemy.com/course/ms-sql-server-70-764/learn/lecture/8579018#overview](https://www.udemy.com/course/ms-sql-server-70-764/learn/lecture/8579018#overview) - 70-764 Course
- [https://www.udemy.com/course/ms-sql-server-70-765/learn/lecture/8579348?start=0#content](https://www.udemy.com/course/ms-sql-server-70-765/learn/lecture/8579348?start=0#content) - 70-765 Course
- [https://www.udemy.com/course/professional-azure-sql-database-administration/learn/lecture/11937264#overview](https://www.udemy.com/course/professional-azure-sql-database-administration/learn/lecture/11937264#overview) - Has good reviews but seems to be reading out the Professional Azure SQL Book from above, word for word?

## Plan and Implement Data Platform Resources (15-20%)

### Deploy resources by using manual methods

**MSLearn Resources**

Provision Azure SQL DB - [https://docs.microsoft.com/en-gb/learn/modules/provision-azure-sql-db/](https://docs.microsoft.com/en-gb/learn/modules/provision-azure-sql-db/)

Provision and Elastic Pool - [https://docs.microsoft.com/en-gb/learn/modules/scale-sql-databases-elastic-pools/](https://docs.microsoft.com/en-gb/learn/modules/scale-sql-databases-elastic-pools/)

Provision PostGres - [https://docs.microsoft.com/en-gb/learn/modules/create-azure-db-for-postgresql-server/](https://docs.microsoft.com/en-gb/learn/modules/create-azure-db-for-postgresql-server/)

SQL on Linux - [https://docs.microsoft.com/en-gb/learn/modules/deploy-sql-server-linux/](https://docs.microsoft.com/en-gb/learn/modules/deploy-sql-server-linux/)

- deploy database offerings on selected platforms
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-single-database-get-started](https://docs.microsoft.com/en-gb/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-iaas-overview?toc=%2Fazure%2Fvirtual-machines%2Fwindows%2Ftoc.json#create-and-manage-azure-sql-resources-with-the-azure-portal)
    - [https://github.com/microsoft/sqlworkshops-azuresqlworkshop/blob/master/azuresqlworkshop/02-DeployAndConfigure.md](https://github.com/microsoft/sqlworkshops-azuresqlworkshop/blob/master/azuresqlworkshop/02-DeployAndConfigure.md)
    - [https://docs.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server-from-the-command-prompt?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server-from-the-command-prompt?view=sql-server-ver15)

- configure customized deployment templates
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-ps-sql-create](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-ps-sql-create)
    - [https://docs.microsoft.com/en-gb/azure/virtual-machines/windows/sql/virtual-machines-windows-portal-sql-server-provision](https://docs.microsoft.com/en-gb/azure/virtual-machines/windows/sql/virtual-machines-windows-portal-sql-server-provision)
    - [https://docs.microsoft.com/en-us/powershell/module/az.compute/set-azvmsourceimage?view=azps-3.8.0](https://docs.microsoft.com/en-us/powershell/module/az.compute/set-azvmsourceimage?view=azps-3.8.0)
    - [https://docs.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server-using-a-configuration-file?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/install-sql-server-using-a-configuration-file?view=sql-server-ver15)

- apply patches and updates for hybrid and IaaS deployment
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-register-with-resource-provider?tabs=azure-powershell%2Cbash#code-try-1](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-register-with-resource-provider?tabs=azure-powershell%2Cbash#code-try-1)
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-agent-extension](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-agent-extension)

### Recommend an appropriate database offering based on specific requirements

- evaluate requirements for the deployment
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-paas-vs-sql-server-iaas)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/features-comparison](https://docs.microsoft.com/en-us/azure/azure-sql/database/features-comparison)
    - [https://github.com/microsoft/sqlworkshops-azuresqlworkshop/blob/master/azuresqlworkshop/01-IntroToAzureSQL.md](https://github.com/microsoft/sqlworkshops-azuresqlworkshop/blob/master/azuresqlworkshop/01-IntroToAzureSQL.md)

- evaluate the functional benefits/impact of possible database offerings
    - [https://docs.microsoft.com/en-us/sql/sql-server/editions-and-components-of-sql-server-version-15?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/sql-server/editions-and-components-of-sql-server-version-15?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/single-database-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/single-database-overview)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-pool-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-pool-overview)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview](https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/sql-managed-instance-paas-overview)

- evaluate the scalability of the possible database offering
- evaluate the HA/DR of the possible database offering
    - sql vm - (Avail group, failover cluster, Log Shipping, Backup & Restore)
- evaluate the security aspects of the possible database offering
    - Security sections of docs listed under funcitonality benefits/offerings

### Configure resources for scale and performance

- configure Azure SQL database/elastic pools for scale and performance
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool)
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool-manage](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-pool-manage)
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-performance-guidance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-performance-guidance)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-pool-scale](https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-pool-scale)

- configure Azure SQL managed instances for scale and performance
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance)
    - Scaling: [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance#managed-instance-service-tiers](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-managed-instance#managed-instance-service-tiers)
- configure SQL Server in Azure VMs for scale and performance
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-performance](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-performance)
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration)
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disks-types#disk-size](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/disks-types#disk-size)

- calculate resource requirements
    - [https://www.spotlightcloud.io/blog/what-is-dtu-in-azure-sql-database-and-how-much-do-we-need](https://www.spotlightcloud.io/blog/what-is-dtu-in-azure-sql-database-and-how-much-do-we-need)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-pool-overview#how-do-i-choose-the-correct-pool-size](https://docs.microsoft.com/en-us/azure/azure-sql/database/elastic-pool-overview#how-do-i-choose-the-correct-pool-size)

- evaluate database partitioning techniques, such as database sharding
    - [https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning](https://docs.microsoft.com/en-us/azure/architecture/best-practices/data-partitioning)
    - [https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding](https://docs.microsoft.com/en-us/azure/architecture/patterns/sharding)
        - Used in sharding - [https://docs.microsoft.com/en-us/azure/sql-database/elastic-jobs-overview](https://docs.microsoft.com/en-us/azure/sql-database/elastic-jobs-overview)
    - [https://app.pluralsight.com/library/courses/microsoft-azure-optimizing-data-solutions/table-of-contents](https://app.pluralsight.com/library/courses/microsoft-azure-optimizing-data-solutions/table-of-contents)
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-introduction](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-elastic-scale-introduction)

### Evaluate a strategy for moving to Azure

Azure SQL Labs - Migration Lab

[https://github.com/microsoft/sqlworkshops-azuresqllabs](https://github.com/microsoft/sqlworkshops-azuresqllabs)

Learn  - Data Migration Assistant

[https://docs.microsoft.com/learn/modules/assess-convert-sql-server-databases-using-dma/](https://docs.microsoft.com/learn/modules/assess-convert-sql-server-databases-using-dma/)

Learn - Migrate to Managed Instance

[https://docs.microsoft.com/en-gb/learn/modules/migrate-sql-workloads-azure-managed-instances/](https://docs.microsoft.com/en-gb/learn/modules/migrate-sql-workloads-azure-managed-instances/)

Learn - Migrate to SQL Azure VMs

[https://docs.microsoft.com/en-gb/learn/modules/migrate-sql-workloads-azure-virtual-machines/](https://docs.microsoft.com/en-gb/learn/modules/migrate-sql-workloads-azure-virtual-machines/)

Learn - Migrate Postgres

[https://docs.microsoft.com/en-gb/learn/modules/migrate-on-premises-postgresql-databases/](https://docs.microsoft.com/en-gb/learn/modules/migrate-on-premises-postgresql-databases/)

Learn - Migrate MySQL

[https://docs.microsoft.com/en-gb/learn/modules/migrate-on-premises-mysql-databases/](https://docs.microsoft.com/en-gb/learn/modules/migrate-on-premises-mysql-databases/)

Data Migration Service

[https://docs.microsoft.com/en-gb/azure/dms/](https://docs.microsoft.com/en-gb/azure/dms/)

- evaluate requirements for the migration
    - [https://docs.microsoft.com/en-us/sql/dma/dma-assesssqlonprem?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/dma/dma-assesssqlonprem?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/azure/dms/pre-reqs](https://docs.microsoft.com/en-us/azure/dms/pre-reqs)

- evaluate offline or online migration strategies
    - [https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-to-azure-sql](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-to-azure-sql)
    - [https://datamigration.microsoft.com/scenario/sql-to-azuresqldb](https://datamigration.microsoft.com/scenario/sql-to-azuresqldb)

- evaluate requirements for the upgrade
    - [https://docs.microsoft.com/en-us/sql/database-engine/install-windows/supported-version-and-edition-upgrades-version-15?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/supported-version-and-edition-upgrades-version-15?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/database-engine/install-windows/supported-version-and-edition-upgrades-version-15#pre-upgrade-checklist](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/supported-version-and-edition-upgrades-version-15#pre-upgrade-checklist)

- evaluate offline or online upgrade strategies
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-manage-application-rolling-upgrade](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-manage-application-rolling-upgrade)

### Implement a migration or upgrade strategy for moving to Azure

MS Learn

- [https://docs.microsoft.com/en-gb/learn/paths/migrate-sql-workloads-azure/](https://docs.microsoft.com/en-gb/learn/paths/migrate-sql-workloads-azure/)
- [https://docs.microsoft.com/en-gb/learn/paths/sql-server-2017-upgrades/](https://docs.microsoft.com/en-gb/learn/paths/sql-server-2017-upgrades/)

- implement an online migration strategy
    - [https://datamigration.microsoft.com/scenario/sql-to-azuresqldb?step=1](https://datamigration.microsoft.com/scenario/sql-to-azuresqldb?step=1)
    - [https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-azure-sql-online](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-azure-sql-online)

- implement an offline migration strategy
    - [https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-to-azure-sql](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-to-azure-sql)
    - 
- implement an online upgrade strategy
    - [https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-managed-instance-online](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-managed-instance-online)
    - [https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-azure-sql-online](https://docs.microsoft.com/en-us/azure/dms/tutorial-sql-server-azure-sql-online)

- implement an offline upgrade strategy
    - [https://docs.microsoft.com/en-us/sql/database-engine/install-windows/upgrade-to-a-different-edition-of-sql-server-setup?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/upgrade-to-a-different-edition-of-sql-server-setup?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/database-engine/install-windows/upgrade-to-a-different-edition-of-sql-server-setup](https://docs.microsoft.com/en-us/sql/database-engine/install-windows/upgrade-to-a-different-edition-of-sql-server-setup)

## Implement a Secure Environment (15-20%)

MSLearn

h[ttps://docs.microsoft.com/en-gb/learn/modules/secure-your-azure-sql-database/](https://docs.microsoft.com/en-gb/learn/modules/secure-your-azure-sql-database/)

- [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-security-overview](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-security-overview)
- [https://app.pluralsight.com/library/courses/microsoft-ignite-session-45/transcript](https://app.pluralsight.com/library/courses/microsoft-ignite-session-45/transcript) - Whats new in SQL Security

### Configure database authentication by using platform and database tools

- configure Azure AD authentication
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-aad-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-aad-overview)
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication-configure?tabs=azure-powershell](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-aad-authentication-configure?tabs=azure-powershell)

- create users from Azure AD identities
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-aad-configure?tabs=azure-powershell#azure-ad-admin-with-a-server-in-sql-database](https://docs.microsoft.com/en-us/azure/azure-sql/database/authentication-aad-configure?tabs=azure-powershell#azure-ad-admin-with-a-server-in-sql-database)

- configure security principals
    - [https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/principals-database-engine?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/principals-database-engine?view=sql-server-ver15)

### Configure database authorization by using platform and database tools

- configure database and object-level permissions using graphical tools
- apply principle of least privilege for all securables
[https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/database-level-roles?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/security/authentication-access/database-level-roles?view=sql-server-ver15)

### Implement security for data at rest

- implement Transparent Data Encryption (TDE)
    - [https://docs.microsoft.com/en-us/azure/sql-database/transparent-data-encryption-azure-sql?tabs=azure-portal](https://docs.microsoft.com/en-us/azure/sql-database/transparent-data-encryption-azure-sql?tabs=azure-portal)
    - [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-ps-sql-keyvault](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-ps-sql-keyvault)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/move-a-tde-protected-database-to-another-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/move-a-tde-protected-database-to-another-sql-server?view=sql-server-ver15)

- implement object-level encryption
    - [https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/encrypt-a-column-of-data?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/encrypt-a-column-of-data?view=sql-server-ver15)
    - 
- implement Dynamic Data Masking
    - Partial vs Default
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-dynamic-data-masking-get-started](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-dynamic-data-masking-get-started)
    - 
- implement Azure Key Vault and disk encryption for Azure VMs
    - [https://docs.microsoft.com/en-us/azure/security/fundamentals/azure-disk-encryption-vms-vmss](https://docs.microsoft.com/en-us/azure/security/fundamentals/azure-disk-encryption-vms-vmss)

### Implement security for data in transit

- configure SQL DB and database-level firewall rules

    [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-firewall-configure](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-firewall-configure)

- implement Always Encrypted
    - [https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/always-encrypted-certificate-store-configure?view=sql-server-ver15](https://docs.microsoft.com/en-us/azure/azure-sql/database/always-encrypted-certificate-store-configure?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/always-encrypted-azure-key-vault-configure?view=sql-server-ver15&tabs=azure-powershell](https://docs.microsoft.com/en-us/azure/azure-sql/database/always-encrypted-azure-key-vault-configure?view=sql-server-ver15&tabs=azure-powershell)

- configure Azure Data Gateway
    - [https://techcommunity.microsoft.com/t5/azure-sql-database/integrate-microsoft-cloud-services-with-your-azure-sql-database/ba-p/1083543](https://techcommunity.microsoft.com/t5/azure-sql-database/integrate-microsoft-cloud-services-with-your-azure-sql-database/ba-p/1083543)
    - [https://docs.microsoft.com/en-us/data-integration/gateway/service-gateway-install](https://docs.microsoft.com/en-us/data-integration/gateway/service-gateway-install)

### Implement compliance controls for sensitive data

- apply a data classification strategy
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-advanced-data-security](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-advanced-data-security)

- configure server and database audits
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-auditing](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-auditing)

- implement data change tracking
    - [https://docs.microsoft.com/en-us/sql/relational-databases/track-changes/about-change-tracking-sql-server?view=sql-server-2017](https://docs.microsoft.com/en-us/sql/relational-databases/track-changes/about-change-tracking-sql-server?view=sql-server-2017)

- perform vulnerability assessment
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-vulnerability-assessment](https://docs.microsoft.com/en-us/azure/sql-database/sql-vulnerability-assessment)

## Monitor and Optimize Operational Resources (15-20%)

[https://docs.microsoft.com/en-us/azure/sql-database/sql-database-monitoring-tuning-index](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-monitoring-tuning-index)

### Monitor activity and performance

- prepare an operational performance baseline
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/establish-a-performance-baseline?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/establish-a-performance-baseline?view=sql-server-ver15)
    - [https://www.sqlservercentral.com/steps/capturing-baselines-on-sql-server-wait-statistics](https://www.sqlservercentral.com/steps/capturing-baselines-on-sql-server-wait-statistics)

- determine sources for performance metrics
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/performance-monitoring-and-tuning-tools?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/performance-monitoring-and-tuning-tools?view=sql-server-ver15)
    - 
- interpret performance metrics
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/query-performance-insight-use](https://docs.microsoft.com/en-us/azure/azure-sql/database/query-performance-insight-use)

- assess database performance by using Azure SQL Database Intelligent Performance
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/intelligent-insights-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/intelligent-insights-overview)

- configure and monitor activity and performance at the infrastructure, server, service, and
database levels
- [https://docs.microsoft.com/en-us/azure/azure-monitor/insights/sql-assessment](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/sql-assessment)

### Implement performance-related maintenance tasks

- implement index maintenance tasks
    - [https://docs.microsoft.com/en-us/sql/relational-databases/indexes/reorganize-and-rebuild-indexes?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/indexes/reorganize-and-rebuild-indexes?view=sql-server-ver15)

- implement statistics maintenance tasks
    - [https://docs.microsoft.com/en-us/sql/relational-databases/statistics/modify-statistics?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/statistics/modify-statistics?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/statistics/update-statistics?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/statistics/update-statistics?view=sql-server-ver15)

- configure database auto-tuning
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/automatic-tuning-enable](https://docs.microsoft.com/en-us/azure/azure-sql/database/automatic-tuning-enable)

- automate database maintenance tasks
    - [SQL Agent Jobs: https://docs.microsoft.com/en-us/azure/sql-database/sql-database-job-automation-overview#sql-agent-jobs](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-job-automation-overview#sql-agent-jobs)
    - [Azure Automation: https://azure.microsoft.com/en-us/blog/azure-automation-your-sql-agent-in-the-cloud/](https://azure.microsoft.com/en-us/blog/azure-automation-your-sql-agent-in-the-cloud/)
    - [SQL Server Agent Jobs: https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-job](https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-job?view=sql-server-ver15)

- manage storage capacity
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-file-space-management](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-file-space-management)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices#disks-guidance](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices#disks-guidance)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/databases/sql-server-data-files-in-microsoft-azure?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/databases/sql-server-data-files-in-microsoft-azure?view=sql-server-ver15)

### Identify performance-related issues

MSLearn

[https://docs.microsoft.com/en-gb/learn/modules/automatically-tune-sql-server-linux/](https://docs.microsoft.com/en-gb/learn/modules/automatically-tune-sql-server-linux/) 

- the github repo doesn't exist, cloned gitmemory version to [https://github.com/stevensnicole/automatically-tune-sql-server-linux](https://github.com/stevensnicole/automatically-tune-sql-server-linux)

[https://docs.microsoft.com/en-gb/learn/modules/use-sql-server-query-tuning-assistant/](https://docs.microsoft.com/en-gb/learn/modules/use-sql-server-query-tuning-assistant/)

- configure Query Store to collect performance data
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/best-practice-with-the-query-store?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/best-practice-with-the-query-store?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15)

- identify sessions that cause blocking
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/intelligent-insights-troubleshoot-performance](https://docs.microsoft.com/en-us/azure/azure-sql/database/intelligent-insights-troubleshoot-performance)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/monitoring-with-dmvs#monitoring-blocked-queries](https://docs.microsoft.com/en-us/azure/azure-sql/database/monitoring-with-dmvs#monitoring-blocked-queries)

- assess growth/fragmentation of databases and logs
    - [https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-instant-file-initialization?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-instant-file-initialization?view=sql-server-ver15)

- assess performance-related database configuration parameters
    - including AutoClose, AutoShrink, AutoGrowth
        - AutoClose - I've never turned this off? Nod to Azure policy maybe? [https://docs.microsoft.com/en-us/sql/relational-databases/policy-based-management/set-the-auto-close-database-option-to-off?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/policy-based-management/set-the-auto-close-database-option-to-off?view=sql-server-ver15)

### Configure resources for optimal performance

- configure storage and infrastructure resources

    [https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration](https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-storage-configuration)

    - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/storage-configuration](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/storage-configuration)
    - [https://docs.microsoft.com/en-gb/learn/modules/migrate-sql-workloads-azure-virtual-machines/2-considerations-sql-server](https://docs.microsoft.com/en-gb/learn/modules/migrate-sql-workloads-azure-virtual-machines/2-considerations-sql-server)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/databases/sql-server-data-files-in-microsoft-azure?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/databases/sql-server-data-files-in-microsoft-azure?view=sql-server-ver15)
    - optimize IOPS, throughput, and latency
        - optimize tempdb performance
            - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices) - search for tempdb
            - [https://docs.microsoft.com/en-us/sql/relational-databases/databases/tempdb-database?view=sql-server-ver15#optimizing-tempdb-performance-in-sql-server](https://docs.microsoft.com/en-us/sql/relational-databases/databases/tempdb-database?view=sql-server-ver15#optimizing-tempdb-performance-in-sql-server)
        - optimize data and log files for performance
            - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices#disks-guidance](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices#disks-guidance)
        - configure server and service account settings for performance
            - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices#feature-specific-guidance](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/performance-guidelines-best-practices#feature-specific-guidance)
        - configure Resource Governor for performance
            - [https://docs.microsoft.com/en-us/sql/relational-databases/resource-governor/resource-governor?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/resource-governor/resource-governor?view=sql-server-ver15)

### Configure a user database for optimal performance

- implement database-scoped configuration
    - [https://docs.microsoft.com/en-us/sql/t-sql/statements/alter-database-scoped-configuration-transact-sql?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/t-sql/statements/alter-database-scoped-configuration-transact-sql?view=sql-server-ver15)
- configure compute resources for scaling
    - Smells like SQL Scale Set, ugh in prod?? or..
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/serverless-tier-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/serverless-tier-overview)
- configure Intelligent Query Processing (IQP)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/intelligent-query-processing?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/intelligent-query-processing?view=sql-server-ver15)

## Perform Automation of Tasks (10-15%)

### Create scheduled tasks

- manage schedules for regular maintenance jobs
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/automation-manage](https://docs.microsoft.com/en-us/azure/azure-sql/database/automation-manage)
- configure multi-server automation
    - [https://docs.microsoft.com/en-us/sql/ssms/agent/automated-administration-across-an-enterprise?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/ssms/agent/automated-administration-across-an-enterprise?view=sql-server-ver15)
- configure notifications for task success/failure/non-completion
    - [https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-sql-server-agent-proxy?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-sql-server-agent-proxy?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-sql-server-agent-proxy?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/ssms/agent/create-a-sql-server-agent-proxy?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/ssms/agent/create-an-operator?view=sql-server-ver15#TsqlProcedure](https://docs.microsoft.com/en-us/sql/ssms/agent/create-an-operator?view=sql-server-ver15#TsqlProcedure)

### Evaluate and implement an alert and notification strategy

- create event notifications based on metrics
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/metrics-diagnostic-telemetry-logging-streaming-export-configure?tabs=azure-portal](https://docs.microsoft.com/en-us/azure/azure-sql/database/metrics-diagnostic-telemetry-logging-streaming-export-configure?tabs=azure-portal)

- create event notifications for Azure resources
    - [https://docs.microsoft.com/en-us/azure/azure-monitor/platform/action-groups](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/action-groups)

- create alerts for server configuration changes
    - [https://docs.microsoft.com/en-us/azure/azure-monitor/insights/sql-assessment](https://docs.microsoft.com/en-us/azure/azure-monitor/insights/sql-assessment)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/alerts-insights-configure-portal](https://docs.microsoft.com/en-us/azure/azure-sql/database/alerts-insights-configure-portal)

- create tasks that respond to event notifications
    - [https://docs.microsoft.com/en-us/sql/relational-databases/service-broker/event-notifications?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/service-broker/event-notifications?view=sql-server-ver15)

### Manage and automate tasks in Azure

- perform automated deployment methods for resources
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/arm-templates-content-guide?tabs=single-database](https://docs.microsoft.com/en-us/azure/azure-sql/database/arm-templates-content-guide?tabs=single-database)
    - https://github.com/Azure/azure-quickstart-templates/tree/master/101-sql-elastic-pool-create
    - https://github.com/Azure/azure-quickstart-templates/tree/master/101-sql-logical-server
    - [https://github.com/Azure/azure-quickstart-templates/tree/master/101-sql-vm-new-storage](https://github.com/Azure/azure-quickstart-templates/tree/master/101-sql-vm-new-storage)

- automate Backups
    - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/automated-backup](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/automated-backup)
    
- automate performance tuning and patching
    - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/automated-patching](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/automated-patching)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/database-advisor-implement-performance-recommendations](https://docs.microsoft.com/en-us/azure/azure-sql/database/database-advisor-implement-performance-recommendations)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/automatic-tuning-enable](https://docs.microsoft.com/en-us/azure/azure-sql/database/automatic-tuning-enable)
    
- implement policies by using automated evaluation modes
    - Azure Policy?

## Plan and Implement a High Availability and Disaster Recovery (HADR) Environment (15-20%)

### Recommend an HADR strategy for a data platform solution

[https://docs.microsoft.com/en-us/azure/azure-sql/database/business-continuity-high-availability-disaster-recover-hadr-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/business-continuity-high-availability-disaster-recover-hadr-overview)

- recommend HADR strategy based on RPO/RTO requirements
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/business-continuity-high-availability-disaster-recover-hadr-overview#recover-a-database-to-the-existing-server](https://docs.microsoft.com/en-us/azure/azure-sql/database/business-continuity-high-availability-disaster-recover-hadr-overview#recover-a-database-to-the-existing-server)
- evaluate HADR for hybrid deployments
    - [https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/business-continuity-high-availability-disaster-recovery-hadr-overview](https://docs.microsoft.com/en-us/azure/azure-sql/virtual-machines/windows/business-continuity-high-availability-disaster-recovery-hadr-overview)
- evaluate Azure-specific HADR solutions
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/high-availability-sla](https://docs.microsoft.com/en-us/azure/azure-sql/database/high-availability-sla)
- identify resources for HADR solutions

### Test an HADR strategy by using platform, OS and database tools

test HA by using failover

[https://docs.microsoft.com/en-us/azure/azure-sql/database/move-resources-across-regions](https://docs.microsoft.com/en-us/azure/azure-sql/database/move-resources-across-regions)

test DR by using failover or restore

[https://docs.microsoft.com/en-gb/azure/sql-database/sql-database-auto-failover-group?tabs=azure-powershell](https://docs.microsoft.com/en-gb/azure/sql-database/sql-database-auto-failover-group?tabs=azure-powershell)

### Perform backup and restore a database by using database tools

[https://docs.microsoft.com/learn/modules/backup-restore-azure-sql/](https://docs.microsoft.com/learn/modules/backup-restore-azure-sql/)

- perform a database backup with options
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/sql-server-backup-to-url?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/sql-server-backup-to-url?view=sql-server-ver15)

- perform a database restore with options
    - [https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/restore-sample-database-quickstart](https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/restore-sample-database-quickstart)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-transaction-log-backup-sql-server](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-transaction-log-backup-sql-server)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/tail-log-backups-sql-server](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/tail-log-backups-sql-server)
    
- perform a database restore to a point in time
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-sql-server-database-to-a-point-in-time-full-recovery-model?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-sql-server-database-to-a-point-in-time-full-recovery-model?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/recovery-using-backups](https://docs.microsoft.com/en-us/azure/azure-sql/database/recovery-using-backups)

- configure long-term backup retention
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/long-term-retention-overview](https://docs.microsoft.com/en-us/azure/azure-sql/database/long-term-retention-overview)
    - [https://docs.microsoft.com/en-us/azure/backup/backup-sql-server-database-azure-vms](https://docs.microsoft.com/en-us/azure/backup/backup-sql-server-database-azure-vms)

### Configure DR by using platform and database tools

- configure replication
    - [https://docs.microsoft.com/en-us/azure/sql-database/sql-database-active-geo-replication](https://docs.microsoft.com/en-us/azure/sql-database/sql-database-active-geo-replication)
    - [https://docs.microsoft.com/en-us/azure/sql-database/scripts/sql-database-setup-geodr-and-failover-database-powershell](https://docs.microsoft.com/en-us/azure/sql-database/scripts/sql-database-setup-geodr-and-failover-database-powershell)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/replication-transactional-overview](https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/replication-transactional-overview)
    - [https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/replication-between-two-instances-configure-tutorial](https://docs.microsoft.com/en-us/azure/azure-sql/managed-instance/replication-between-two-instances-configure-tutorial)
- configure Azure Site Recovery for a database offering
    - [https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-sql](https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-sql)

### Configure HA using platform, OS and database tools

- create an Availability Group
    - [https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/overview-of-always-on-availability-groups-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/overview-of-always-on-availability-groups-sql-server?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/creation-and-configuration-of-availability-groups-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/creation-and-configuration-of-availability-groups-sql-server?view=sql-server-ver15)

- integrate a database into an Availability Group
    - [https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/join-a-secondary-database-to-an-availability-group-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/join-a-secondary-database-to-an-availability-group-sql-server?view=sql-server-ver15)

- configure quorum options for a Windows Server Failover Cluster
    - [https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/create-or-configure-an-availability-group-listener-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/create-or-configure-an-availability-group-listener-sql-server?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/windows-server/failover-clustering/manage-cluster-quorum](https://docs.microsoft.com/en-us/windows-server/failover-clustering/manage-cluster-quorum)
    - [https://docs.microsoft.com/en-us/windows-server/storage/storage-spaces/understand-quorum](https://docs.microsoft.com/en-us/windows-server/storage/storage-spaces/understand-quorum)

- configure an Availability Group listener
    - [https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/create-or-configure-an-availability-group-listener-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/create-or-configure-an-availability-group-listener-sql-server?view=sql-server-ver15)

### Perform Administration by Using T-SQL (10-15%)

### Examine system health

- evaluate database health using DMVs
    - [https://docs.microsoft.com/en-us/azure/azure-sql/database/monitoring-with-dmvs](https://docs.microsoft.com/en-us/azure/azure-sql/database/monitoring-with-dmvs)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-db-wait-stats-azure-sql-database?view=azuresqldb-current](https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-db-wait-stats-azure-sql-database?view=azuresqldb-current)

- evaluate server health using DMVs
    - [https://docs.microsoft.com/en-us/sql/relational-databases/extended-events/use-the-system-health-session?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/extended-events/use-the-system-health-session?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-os-wait-stats-transact-sql?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-os-wait-stats-transact-sql?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-exec-session-wait-stats-transact-sql?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-exec-session-wait-stats-transact-sql?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-server-diagnostics-transact-sql?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/system-stored-procedures/sp-server-diagnostics-transact-sql?view=sql-server-ver15)

- perform database consistency checks by using DBCC
    - https://docs.microsoft.com/en-us/sql/t-sql/database-console-commands/dbcc-transact-sql?view=sql-server-ver15

### Monitor database configuration by using T-SQL

- assess proper database autogrowth configuration
    - [https://raresql.com/2013/02/19/sql-server-best-way-to-check-all-database-autogrowth-settings/](https://raresql.com/2013/02/19/sql-server-best-way-to-check-all-database-autogrowth-settings/)
- report on database free space
    - [https://blog.sqlauthority.com/2016/06/07/sql-server-much-free-space-database/](https://blog.sqlauthority.com/2016/06/07/sql-server-much-free-space-database/)
- review database configuration options
    - [https://docs.microsoft.com/en-us/sql/database-engine/configure-windows/view-or-change-server-properties-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/database-engine/configure-windows/view-or-change-server-properties-sql-server?view=sql-server-ver15)

### Perform backup and restore a database by using T-SQL

- prepare databases for AlwaysOn Availability Groups
    - [https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/manually-prepare-a-secondary-database-for-an-availability-group-sql-server?view=sql-server-ver15#RelatedTasks](https://docs.microsoft.com/en-us/sql/database-engine/availability-groups/windows/manually-prepare-a-secondary-database-for-an-availability-group-sql-server?view=sql-server-ver15#RelatedTasks)
- perform transaction log backup
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/back-up-a-transaction-log-sql-server?view=sql-server-ver15#using-transact-sql](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/back-up-a-transaction-log-sql-server?view=sql-server-ver15#using-transact-sql)
- perform restore of user databases
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-backup-from-a-device-sql-server?view=sql-server-ver15#TsqlProcedure](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-backup-from-a-device-sql-server?view=sql-server-ver15#TsqlProcedure)
- perform database backups with options
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-sql-server-database-to-a-point-in-time-full-recovery-model?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-a-sql-server-database-to-a-point-in-time-full-recovery-model?view=sql-server-ver15)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-files-to-a-new-location-sql-server?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/restore-files-to-a-new-location-sql-server?view=sql-server-ver15)

### Manage authentication by using T-SQL

- manage security principals

### Manage authorization by using T-SQL

- configure permissions for users to access database objects
- configure permissions by using custom roles

## Optimize Query Performance (5-10%)

### Review query plans

- determine the appropriate type of execution plan
    - live Query Statistics, Actual Execution Plan, Estimated Execution Plan, Showplan
        - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-and-save-execution-plans?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-and-save-execution-plans?view=sql-server-ver15)
        - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-the-estimated-execution-plan?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-the-estimated-execution-plan?view=sql-server-ver15)
        - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-an-actual-execution-plan?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/display-an-actual-execution-plan?view=sql-server-ver15)
- identify problem areas in execution plans
- extract query plans from the Query Store
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15#About](https://docs.microsoft.com/en-us/sql/relational-databases/performance/monitoring-performance-by-using-the-query-store?view=sql-server-ver15#About)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/performance/best-practice-with-the-query-store?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/performance/best-practice-with-the-query-store?view=sql-server-ver15)

### Evaluate performance improvements

- determine the appropriate Dynamic Management Views (DMVs) to gather query
performance information
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-exec-sql-text-transact-sql?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-exec-sql-text-transact-sql?view=sql-server-ver15)
- identify performance issues using DMVs
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-os-wait-stats-transact-sql?view=sql-server-2017](https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-os-wait-stats-transact-sql?view=sql-server-2017)
    - [https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-exec-query-stats-transact-sql](https://docs.microsoft.com/en-us/sql/relational-databases/system-dynamic-management-views/sys-dm-exec-query-stats-transact-sql)
- identify and implement index changes for queries
- recommend query construct modifications based on resource usage
- assess the use of hints for query performance

### Review database table and index design

- identify data quality issues with duplication of data
- identify normal form of database
- assess index design for performance
    - [https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-files-and-filegroups?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-files-and-filegroups?view=sql-server-ver15)
- validate data types defined for columns
- recommend table and index storage including filegroups
    - [https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-files-and-filegroups?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/databases/database-files-and-filegroups?view=sql-server-ver15)
- evaluate table partitioning strategy
    - [https://docs.microsoft.com/en-us/sql/relational-databases/partitions/partitioned-tables-and-indexes?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/partitions/partitioned-tables-and-indexes?view=sql-server-ver15)
- evaluate the use of compression for tables and indexes
    - [https://docs.microsoft.com/en-us/sql/relational-databases/data-compression/data-compression?view=sql-server-ver15](https://docs.microsoft.com/en-us/sql/relational-databases/data-compression/data-compression?view=sql-server-ver15)
