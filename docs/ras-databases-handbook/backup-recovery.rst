.. _data-recovery-ras-db-handbook:

Backup, recovery, and restoration
==================================

This section includes a description of the services that Rackspace provides to
ensure that your data is backed up and can be recovered.


Backups and export
-------------------

Hot backup, a backup performed while the database is running, is
included in this service. An export is a conversion of a database to a
text file for maximum portability. The following backup and export tools are
included:

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Oracle Recovery Manager (RMAN) to perform and monitor hot backups
     - * Commvault database, tablespace, and incremental level backups for select
         databases

   * - * Export Data Pump (EXPDP) to automate schema
     - * MySQL backups with mysqldump, mydumper, Percona XtraBackup, and Holland
         Backup
=======
   * - * Oracle RMAN (Recovery Manager) to perform and monitor hot backups
     - * Commvault database, tablespace and incremental level backups for
         select databases

   * - * EXPDP (Export Data Pump) to automate schema
     - * MySQL backups with mysqldump, mydumper, Percona XtraBackup, and
         Holland Backup


Restoration and recovery
-------------------------

Rackspace DBAs have the expertise to recover databases from crashed
states or storage failures. If there is a critical failure in the
infrastructure, DBAs perform the following tasks:

-  Detect the failure (monitoring).

-  Repair the database by using backup data.

-  Escalate additional needs (such as hardware replacement, SEAP-related
   activities, and so on) as necessary.

Data rescue
------------

If a user deletes important data, Rackspace can restore the database
by using the backup files to an earlier time on another server to recover
that data. Clients require redundant database hardware to benefit from
this service. By leveraging such options as Rapid Deployment, Rackspace
can bring new equipment online to quickly respond to a data rescue
emergency.

Replication
------------

Replication limits inconsistencies between software and hardware components
or both, improving reliability, fault-tolerance, and accessibility. Replication
services feature:

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Oracle Data Guard
     - * Sharding and replica sets
   * - * Microsoft SQL Server log shipping
     - * Data refresh using existing backups
   * - * MySQL streaming replication
     - * Building and reporting servers
   * - * DB2 HADR
     - * Export and import process at schema level
