Data
===================

Application takes use of spatial and non spatial data accessed from files and database.

Data Storage
^^^^^
Database
////
Data is stored and served from `Postgresql <https://www.postgresql.org/>`_
Database enabled with **PostGis**.

DB Name: ``uitrit4``

DB Schema: ``uitrit0``

Database Structure and Mapping
*******

.. csv-table:: Data
   :file: /static/DBMapping.csv
   :widths: 30, 70
   :header-rows: 1


File Storage
////

Data is Stored in GISdata Directory found at ``/usr/GISdata`` on the server.

Structure of Directory:
*******
.. image:: /static/DatabaseDir.png



