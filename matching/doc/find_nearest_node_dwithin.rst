.. 
   ****************************************************************************
    pgRouting Manual
    Copyright(c) pgRouting Contributors

    This documentation is licensed under a Creative Commons Attribution-Share  
    Alike 3.0 License: http://creativecommons.org/licenses/by-sa/3.0/
   ****************************************************************************

.. _pgr_find_nearest_node_dwithin:

pgr_findNearestNodeDWithin - Find nearest node within distance
===============================================================================

.. index:: 
  single: pgr_findNearestNodeDWithin(varchar,double precision,varchar)
  module: matching

Name
-------------------------------------------------------------------------------

``pgr_findNearestNodeDWithin`` — Finds the nearest node to a given node.


Synopsis
-------------------------------------------------------------------------------

The function finds and returns the nearest node to a given node.

.. code-block:: sql

  integer pgr_findNearestNodeDWithin(varchar point, double precision distance, varchar geom_table);


Description
-------------------------------------------------------------------------------

:point: ``varchar`` text representation of the point
:distance: ``float8`` function will search for a node within this distance
:geom_table: ``varchar`` network table name (may contain the schema name as well)


.. rubric:: History

* Moved to pgrouting-contrib repository


Examples
-------------------------------------------------------------------------------

.. code-block:: sql

  [TBD]


See Also
-------------------------------------------------------------------------------

* [TBD]
