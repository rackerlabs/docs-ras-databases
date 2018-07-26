.. _planning-ras-db-handbook:

PLANNING
=========

Intro text here...

CAPACITY PLANNING
------------------

DBAs apply their experience and training to help clients determine their
potential storage needs. Administrators work collaboratively with
clients to:

-  Design and deploy database infrastructure that can be scaled up with
   new demands (as opposed to a rebuild)
-  Identify disk space shortages and recommend workarounds before they
   impact normal operations
-  Assist with determining when RAM or CPU upgrades will benefit overall
   DB workloads

STORAGE ARCHITECTURE
---------------------

In order for databases to properly function, it is critical to plan and
deploy databases on a proper storage underpinning. Ensuring proper disk
storage implementation allows for the isolation of performance
bottlenecks. DBAs are responsible for performing the following task as
necessary:

-  Separating the OS from the database at the disk layer
-  Separating the database from the backup disks
-  Isolating I/O bottleneck areas to discrete disk storage that can be
   tuned for the required workloads. These tasks are performed on SAN
   storage and local storage.
