About
=====

Date and time in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-time

Example
========

.. code-block:: python

   from time.system import now as system_now
   from time.steady import now as steady_now
   from time import LocalDateTime
   from time import UtcDateTime

   def main():
       print("system_now():    ", system_now())
       print("steady_now():    ", steady_now())
       print("LocalDateTime(): ", LocalDateTime())
       print("UtcDateTime():   ", UtcDateTime())

Functions and types
===================

Time
----

.. mysfile:: src/lib.mys

System time
-----------

.. mysfile:: src/system.mys

Steady time
-----------

.. mysfile:: src/steady.mys

.. _Mys programming language: https://mys.readthedocs.io/en/latest/
