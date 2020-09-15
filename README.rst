|buildstatus|_

Time
====

Date and time in the `Mys programming language`_.

Examples
========

.. code-block:: python

   from time.system import now as system_now
   from time.steady import now as steady_now
   from time import DateTime

   def main():
       print('system.now():', system_now())
       print('steady.now():', steady_now())
       print('DateTime:    ', DateTime.from_time(system_now()))

.. code-block:: text

   $ mys run
   system.now(): Time(seconds=1600112736, nanoseconds=5209582)
   steady.now(): Time(seconds=174436, nanoseconds=359)
   DateTime:     DateTime(year=2020, month=9, day=14, hour=19, minute=1, second=34)


.. |buildstatus| image:: https://travis-ci.com/eerimoq/mys-time.svg?branch=master
.. _buildstatus: https://travis-ci.com/eerimoq/mys-time

.. _Mys programming language: https://github.com/eerimoq/mys
