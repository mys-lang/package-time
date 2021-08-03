|discord|_
|test|_
|stars|_

About
=====

Date and time in the `Mys programming language`_.

Project: https://github.com/mys-lang/package-time

Example
========

Just print dates and times.

.. code-block:: mys

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

.. code-block:: myscon

   ❯ mys run
    ✔ Reading package configuration (0 seconds)
    ✔ Building (0.22 seconds)
   system_now():     Time(seconds=1617085725, nanoseconds=591346000)
   steady_now():     Time(seconds=2147009, nanoseconds=643340000)
   LocalDateTime():  2021-03-30 08:28:45
   UtcDateTime():    2021-03-30 06:28:45 UTC

API
===

Time
----

.. mysfile:: src/lib.mys

System time
-----------

.. mysfile:: src/system.mys

Steady time
-----------

.. mysfile:: src/steady.mys

.. |discord| image:: https://img.shields.io/discord/777073391320170507?label=Discord&logo=discord&logoColor=white
.. _discord: https://discord.gg/GFDN7JvWKS

.. |test| image:: https://github.com/mys-lang/package-time/actions/workflows/pythonpackage.yml/badge.svg
.. _test: https://github.com/mys-lang/package-time/actions/workflows/pythonpackage.yml

.. |stars| image:: https://img.shields.io/github/stars/mys-lang/package-time?style=social
.. _stars: https://github.com/mys-lang/package-time

.. _Mys programming language: https://mys-lang.org
