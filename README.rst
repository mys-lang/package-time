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
       print("system_now():", system_now())
       print("steady_now():", steady_now())
       print("DateTime:    ", DateTime(system_now()))

.. code-block:: text

   $ mys run
   system_now(): Time(seconds=1615134755, nanoseconds=215459607)
   steady_now(): Time(seconds=199755, nanoseconds=6931116)
   DateTime:     DateTime(year=2021, month=3, day=7, hour=17, minute=32, second=35)

.. _Mys programming language: https://github.com/mys-lang/mys
