.. _planning-ras-db-handbook:

Planning
=========

This section describes the following forms of planning to consider when deploying
databases.

- Capacity planning identifies your immediate and long-term storage
  needs.
- Storage architecture planning addresses the underlying architecture
  required to support those needs.

Capacity planning
------------------

DBAs apply their experience and training to help clients determine their
potential storage needs. Administrators work collaboratively with
clients to perform the following tasks:

-  Design and deploy database infrastructure that can be scaled up with
   new demands (as opposed to a rebuild).
-  Identify disk space shortages and recommend workarounds before they
   impact normal operations.
-  Assist with determining when RAM or CPU upgrades will benefit overall
   DB workloads.

Storage architecture
---------------------

In order for databases to properly function, it is critical to plan and
deploy databases on the proper storage underpinning. Ensuring proper disk
storage implementation allows for the isolation of performance
bottlenecks. DBAs are responsible for performing the following task as
necessary:

-  Separating the OS from the database at the disk layer.
-  Separating the database from the backup disks.
-  Isolating I/O bottleneck areas to discrete disk storage that can be
   tuned for the required workloads. These tasks are performed on storage area
   network (SAN) storage and local storage.
