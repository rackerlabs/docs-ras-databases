.. _reporting-ras-db-handbook:

Database reporting
===================

In order to provide clients with active status updates for their
databases and associated content, Oracle, Microsoft SQL, and MySQL databases are
configured to generate the following reports:

.. _oracle-1:

Oracle
-------

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * I/O statistics
     - * Automatic Workload Repository (AWR) and Automatic Database Diagnostic
         Monitor (ADDM) reports when licensed for Oracle Enterprise Edition
   * - * Backup success
     - * Low disk space in database volumes
   * - * Blocking sessions
     - * Memory and CPU utilization
   * - * Connection counts
     - * Oracle listener response
   * - * Custom content checks
     - * Replication technologies

Microsoft SQL Server
---------------------

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Backup success
     - * I/O statistics
   * - * Blocking sessions
     - * Low disk space in database volumes
   * - * Custom content check
     - * Memory and CPU utilization
   * - * Custom thresholds
     - * Microsoft SQL job monitoring
   * - * Data file utilization
     - * Replication technologies
   * - * Database growth
     - * Restart check
   * - * Deadlock detection
     -

MySQL
------

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Backup connection success
     - * Low disk space in database volumes ICS
   * - * Custom content check
     - * Memory and CPU utilization
   * - * Database growth
     - * Network listener response
   * - * I/O Statistics
     - * Replication technologies

DB2
----

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Backup success
     - * Health monitor
   * - * Database growth
     - * Memory and CPU utilization
   * - * Deadlock detection
     - * Tablespace containers utilization

Datastax Enterprise Apache Cassandra
-------------------------------------

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Backup success
     - * Memory and CPU utilization
   * - * Connection counts
     - * Network listener response
   * - * Custom content check
     - * OpsCenter report
   * - * I/O statistics
     - * Replication technologies
   * - * Low disk space in database volumes
     -

MongoDB
--------

.. list-table::
   :widths: 20 50
   :header-rows: 0

   * - * Backup success
     - * Memory and CPU utilization
   * - * Connection counts
     - * MMS reports
   * - * I/O statistics
     - * Network listener response
   * - * Low disk space in database volumes
     - * Replication technologies
