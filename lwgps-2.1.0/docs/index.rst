LwGPS |version| documentation
=============================

Welcome to the documentation for version |version|.

LwGPS is lightweight, platform independent library to parse NMEA statements from GPS receivers. It is highly optimized for embedded systems.

.. rst-class:: center
.. rst-class:: index_links

    :ref:`download_library` :ref:`getting_started` `Open Github <https://github.com/MaJerle/lwgps>`_

Features
^^^^^^^^

* Written in ANSI C99
* Platform independent, easy to use
* Built-in support for 4 GPS statements

  * ``GPGGA`` or ``GNGGA``: GPS fix data
  * ``GPGSA`` or ``GNGSA``: GPS active satellites and dillusion of position
  * ``GPGSV`` or ``GNGSV``: List of satellites in view zone
  * ``GPRMC`` or ``GNRMC``: Recommended minimum specific GPS/Transit data

* Optional ``float`` or ``double`` floating point units
* Low-level layer is separated from application layer, thus allows you to add custom communication with GPS device
* Works with operating systems
* Works with different communication interfaces
* User friendly MIT license

Requirements
^^^^^^^^^^^^

* C compiler
* Driver for receiving data from GPS receiver
* Few *kB* of non-volatile memory

Contribute
^^^^^^^^^^

Fresh contributions are always welcome. Simple instructions to proceed:

#. Fork Github repository
#. Respect `C style & coding rules <https://github.com/MaJerle/c-code-style>`_ used by the library
#. Create a pull request to ``develop`` branch with new features or bug fixes

Alternatively you may:

#. Report a bug
#. Ask for a feature request

License
^^^^^^^

.. literalinclude:: ../LICENSE

Table of contents
^^^^^^^^^^^^^^^^^

.. toctree::
  :maxdepth: 2

  self
  get-started/index
  user-manual/index
  api-reference/index
  examples/index

