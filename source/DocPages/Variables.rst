Variables
+++++++++

Grammar
-------
Variable Declaration
====================
``<ID>`` : ``<TYPE>`` = ``<EXPR>`` ;

Variable Assignment
===================
``<ID>`` = ``<EXPR>`` ;

Examples
--------

Simple Variable Declaration
===========================
.. code-block:: c

  x: int = 4;

Variable Re-Assignment
======================
.. code-block:: c

  y: int = 4 + (9 - 4);
  y = y + 4;
