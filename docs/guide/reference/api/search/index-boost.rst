.. _es-guide-reference-api-search-index-boost:

===========
Index Boost
===========

Allows to configure different boost level per index when searching across more than one indices. This is very handy when hits coming from one index matter more than hits coming from another index (think social graph where each user has an index).


.. code-block:: js


    {
        "indices_boost" : {
            "index1" : 1.4,
            "index2" : 1.3
        }
    }

