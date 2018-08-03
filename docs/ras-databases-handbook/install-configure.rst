.. _install-config-ras-db-handbook:

Software installation and configuration
========================================

Proper installation and configuration of essential software is critical for
database functionality. Rackspace installs and configures the following
software for a variety of databases:

.. list-table::
   :widths: 50 50
   :header-rows: 0

   * - Oracle

       -  Oracle Grid or Clusterware
       -  Oracle Database
       -  Oracle GoldenGate
       -  Oracle Application Express (APEX)
       -  Oracle client software on computers connecting to the database
     - MySQL

       -  MySQL database software
       -  Enabling master/slave and master/master replication
       -  Oracle Grid or Clusterware with MySQL
       -  MySQL cluster
       -  MariaDB Galera cluster
       -  Percona XtraDB cluster

   * - Microsoft SQL Server

       -  Configuring clustering
       -  Mirroring
       -  Log shipping
       -  Replication
       -  High Availability Disaster Recovery (HADR) configuring and clustering
     - MongoDB

       -  Configuring and installation
       -  Replica sets
       -  Sharding

   * - Cassandra and DataStax Enterprise

       -  Install software
       -  Configure
       -  Replica sets
       -  Sharding
     - PostgreSQL and EnterpriseDB

       -  Install software
       -  Configuring clustering
       -  Replication

   * - Couchbase and CouchDB

       - Install software
       - Configure
       - Replica sets
       - Sharding

     -

Additional database platforms can be supported upon request. Rackspace has a
wide variety of partners who offer support and has Rackers willing to learn a
new technology. If your chosen platform is not already supported, let us know.

Modification and configuration services
----------------------------------------

Though clients are responsible for database content, Rackspace performs
modification and configuration tasks in accordance with explicit client
instructions.

Connectivity management
------------------------

DBAs manage connectivity between the client application and the databases in
order to ensure efficient and uninterrupted communication. Utilizing database
performance tools, DBAs can identify database tasks that are not tuned for
optimal performance. Rackspace assists clients in designing connection pooling
strategies to maximize usability of their database infrastructure. This service
is provided as an initial design requirement or on an on-going basis. The
following performance tools are included:

-  SQL/*Net
-  Java Database Connectivity (JDBC) connection pools
-  Oracle SQL/*Net


Event notification
-------------------

If threshold warning levels exceed a critical parameter, an alert is
sent to the monitoring system. Based on the specific alert, a ticket is
created that notifies the Support team when the client needs to be
contacted. Rackspace collaborates with the client to resolve problems
within an agreed-upon timeframe.
