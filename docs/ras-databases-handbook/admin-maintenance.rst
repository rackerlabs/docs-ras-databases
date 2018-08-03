.. _admin-ras-db-handbook:

Administration and maintenance
===============================

To maintain optimal database performance throughout the lifetime of
client solutions, Rackspace performs the following activities:

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Research, track, and apply vendor database software patches
     - * Monitor and correct health issues
   * - * Assist with data migration from development to quality assurance, and from quality assurance to production
     - * Support Oracle Enterprise Manager DB Console
   * - * Perform and monitor database backups
     - * Support Oracle Grid Control
   * - * Apply database changes at the client’s request
     - * Support MongoDB Monitoring Service (MMS)
   * - * Employ reporting services and analysis services by using native Oracle or third-party tools or both.
     - * Support DataStax OpsCenter


Migration
----------

Migrating databases can be complex, time-consuming, and costly if not executed
properly. Rackspace DBAs analyze, capture, and recreate a clients’ existing
requirements as a part of “go-live”. They also facilitate the following items:

-  Initial environment assessment and recommendations.
-  Client in-house database migrations to Rackspace facilities.
-  Non-Rackspace hosted database migrations to Rackspace facilities.
-  Physical to virtual migrations (P2V) for legacy environments.
-  Vendor-to-vendor migrations (such as, Oracle to Microsoft SQL Server) are
   possible in conjunction with a Professional Services migration
   engagement.

Security management
--------------------

Rackspace advanced security and encryption services help protect
the integrity of client databases and comply with third-party security
standards.

Oracle
~~~~~~~

-  Deploy and configure the advanced security option for tablespace and network
   encryption (TDE).
-  Work with the Rackspace Security team on third-party encryption software
   (TDE).


Microsoft SQL Server
~~~~~~~~~~~~~~~~~~~~~

-  Work with the Rackspace Security team on third-party encryption software
   (TDE).
-  Deploy and configure Microsoft encryption software (TDE).


All other vendors
~~~~~~~~~~~~~~~~~~

-  Work with the Rackspace Security team to deploy Payment Card Industry (PCI)
   compliant solutions.
-  Enable the auditing features built into the database products, as requested.


DB clustering and high availability
------------------------------------

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Oracle Real Application Clusters (RAC)
     - * PostgreSQL on Red Hat clusters
   * - * Oracle Cold Failover clusters
     - * Mongo Replica sets
   * - * Microsoft SQL Server on Windows clusters
     - * Couchbase Replication
   * - * Microsoft SQL Server AlwaysOn
     - * MySQL on Red Hat clusters
   * - * Percona XtraDB clusters
     -


Auditing
---------

Rackspace provides the following customized vendor-supplied auditing features to
assist client compliance objectives:

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Native auditing enablement in the database features, per client
         requirements
     - * Microsoft SQL Server - C2 auditing
   * - * Oracle fine-grain auditing
     - * Microsoft SQL Server - Change tracking
   * - * Oracle total recall flashback data archive
     - * Microsoft SQL Server - Change Data Capture
   * - * Microsoft SQL Server audit
     -
