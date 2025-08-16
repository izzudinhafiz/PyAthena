.. _api_connection:

Connection and Cursors
======================

This section covers the core connection functionality and basic cursor operations.

Connection
----------

.. automodule:: pyathena
   :members: connect

.. autoclass:: pyathena.connection.Connection
   :members:
   :inherited-members:

Standard Cursors
----------------

.. autoclass:: pyathena.cursor.Cursor
   :members:
   :inherited-members:

.. autoclass:: pyathena.cursor.DictCursor
   :members:
   :inherited-members:

Asynchronous Cursors
--------------------

.. autoclass:: pyathena.async_cursor.AsyncCursor
   :members:
   :inherited-members:

.. autoclass:: pyathena.async_cursor.AsyncDictCursor
   :members:
   :inherited-members: