tfdeploy
========

.. centered:: This page contains only API docs. For more info, visit `tfdeploy on GitHub <https://github.com/riga/tfdeploy>`_.


.. toctree::
   :maxdepth: 2


.. automodule:: tfdeploy


Classes
^^^^^^^

``Model``
---------

.. autoclass:: Model
   :member-order: bysource
   :members:


``Tensor``
----------

.. autoclass:: Tensor
   :member-order: bysource
   :members:


``Operation``
-------------

.. autoclass:: Operation
   :member-order: bysource
   :members:


Functions
^^^^^^^^^

``optimize``
------------

.. autofunction:: optimize


Other Attributes
^^^^^^^^^^^^^^^^

.. py:attribute:: IMPL_NUMPY

   Implementation type for ops that use numpy (the default).

.. py:attribute:: IMPL_SCIPY

   Implementation type for ops that use scipy.

.. py:attribute:: HAS_SCIPY

   A flag that is *True* when scipy is available on your system.


Exceptions
^^^^^^^^^^

``UnknownOperationException``
-----------------------------

.. autoexception:: UnknownOperationException


``OperationMismatchException``
------------------------------

.. autoexception:: OperationMismatchException


``InvalidImplementationException``
----------------------------------

.. autoexception:: InvalidImplementationException


``UnknownImplementationException``
----------------------------------

.. autoexception:: UnknownImplementationException


``ScipyOperationException``
---------------------------

.. autoexception:: ScipyOperationException
