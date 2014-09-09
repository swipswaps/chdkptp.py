==========
chdkptp.py
==========

Python bindings for chdkptp_ via an embedded, thread-safe Lua runtime (thanks
to Stefan Behnel's lupa_).

Requirements
============
    - C compiler
    - Lua 5.2, with headers
    - libusb, with headers
    - lupa_, installed with the `--no-luajit` flag

.. _chdkptp: https://www.assembla.com/spaces/chdkptp/wiki
.. _lupa: https://github.com/scoder/lupa

API Reference
=============
.. automodule:: chdkptp
   :members:

.. automodule:: chdkptp.device
   :members: Message

.. automodule:: chdkptp.lua
   :members:

.. automodule:: chdkptp.util
   :members:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
