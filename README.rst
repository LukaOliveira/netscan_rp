NETSCAN-RP
=======

A Python network scan library developed in Rust with PyO3.

About
------------

NETSCAN-RP is intended to be an interface between `qscan Rust libray <https://lib.rs/crates/qscan/>`__ and Python.
Bringing compiled language performance and optimization to Python.


Installation
------------
.. code:: python

   pip install netscan-rp

Examples
------------

SCAN

.. code:: python

   import netscan_rp

   ip_list       = '172.16.0.10,172.16.0.20'
   port_list     = '80,443,21,53'

   scan_result = netscan_rp.scan(ip_list, port_list)

   print(scan_result)

Roadmap
-------

-  Command Line Support

License
-------
MIT

