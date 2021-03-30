|test|_

About
=====

Date and time.

Project: https://github.com/mys-lang/package-time

Example
========

Just print dates and times.

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

Build and run.

.. code-block:: text

   $ mys run
    ✔ Reading package configuration (0 seconds)
    ✔ Building (0.22 seconds)
   system_now():     Time(seconds=1617085725, nanoseconds=591346000)
   steady_now():     Time(seconds=2147009, nanoseconds=643340000)
   LocalDateTime():  2021-03-30 08:28:45
   UtcDateTime():    2021-03-30 06:28:45 UTC

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

.. |test| image:: https://github.com/mys-lang/package-time/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-time/actions/workflows/pythonpackage.yml
