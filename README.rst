|buildstatus|_

Time
====

Date and time facilities in the `Mys programming language`_.

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

.. |buildstatus| image:: https://travis-ci.com/eerimoq/mys-time.svg?branch=master
.. _buildstatus: https://travis-ci.com/eerimoq/mys-time

.. _Mys programming language: https://github.com/eerimoq/mys
