ControlFlow
+++++++++++

.. Admonition
.. important::
  All control flow constructs require a semicolon, ``;``, at the end of their blocks as of now.

.. important::
  All control flow constructs have the capability of holding more statements within their blocks (Examples shown in ``Nested Statements`` sections)

.. =======================
.. If Statment section
.. =======================

If
--
`**Note: No else, or else if... yet**`

.. =======================
.. If statement section
.. =======================

Grammar
=======
``<IF>`` ``<EXPR>`` ``<BLOCK>``

Examples
========

Simple If Statement
```````````````````
.. code-block:: c

  if x == 4 {
    ...
  };

Nested Statements
```````````````````
.. code-block:: c

  if x == 4 {
    if y > x {
      ...
    };
  };

-----

.. =======================
.. While Loop section
.. =======================

While
-----
Grammar
=======
``<WHILE>`` ``<EXPR>`` ``<BLOCK>``

Examples
========

Simple While Loop
`````````````````
.. code-block:: c

  while x > 4 {
    x = x - 1;
  };

Nested Statements
```````````````````
.. code-block:: c

  while x > 4 {
    if x % 2 == 0 {
      ...
    };
    if x % 2 == 1 {
      ...
    };
  };

----

.. =======================
.. For Loop section
.. =======================

For (Not Implemented Yet)
-------------------------
Grammar
=======
``<FOR>`` ``<VAR>|<EXPR>`` ``;`` ``<EXPR>`` ``;`` ``<EXPR>`` ``<BLOCK>``

Examples
========

Simple For Loop
```````````````
.. code-block:: c

  for i: int = 0; i < 4; i = i + 1 {
    
  };
