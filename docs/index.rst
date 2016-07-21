.. redis-py documentation master file, created by
   sphinx-quickstart on Fri Feb  8 00:47:08 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to redis-py's documentation!
====================================


Redis
-------

.. autoclass:: redis.Redis
   :members:

StrictRedis
------------

.. autoclass:: redis.StrictRedis
   :members:

Connections
------------

.. autoclass:: redis.Connection
   :members:

.. autoclass:: redis.ConnectionPool
   :members:

.. autoclass:: redis.BlockingConnectionPool
   :members:

.. autoclass:: redis.SSLConnection
   :members:

.. autoclass:: redis.UnixDomainSocketConnection
   :members:

Utils
------

.. autofunction:: redis.from_url

Exceptions
-----------

.. autoclass:: redis.AuthenticationError
   :members:
.. autoclass:: redis.BusyLoadingError
   :members:
.. autoclass:: redis.ConnectionError
   :members:
.. autoclass:: redis.DataError
   :members:
.. autoclass:: redis.InvalidResponse
   :members:
.. autoclass:: redis.PubSubError
   :members:
.. autoclass:: redis.ReadOnlyError
   :members:
.. autoclass:: redis.RedisError
   :members:
.. autoclass:: redis.ResponseError
   :members:
.. autoclass:: redis.TimeoutError
   :members:
.. autoclass:: redis.WatchError
   :members:


CHANGELOG
----------

.. include:: ../CHANGES


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

