..  _NXxlaue:

#######
NXxlaue
#######

.. index::  ! . NXDL applications; NXxlaue

category:
    applications

NXDL source:
    NXxlaue
    
    (http://svn.nexusformat.org/definitions/trunk/applications/NXxlaue.nxdl.xml)

version:
    1.0b

SVN Id:
    $Id$

extends class:
    :ref:`NXxrot`

other classes included:
    :ref:`NXdata`, :ref:`NXentry`, :ref:`NXinstrument`, :ref:`NXsource`

symbol list:
    none

documentation:
    This is the application definition for raw data from a single crystal laue
    camera. It extends NXxrot.
    


.. rubric:: Basic Structure of **NXxlaue**

::

    NXxlaue (application definition, version 1.0b)
      (overlays NXentry)
      entry:NXentry
        definition:NX_CHAR
        instrument:NXinstrument
          source:NXsource
            distribution:NXdata
              data:NX_CHAR
              wavelength:NX_CHAR
    

.. rubric:: Comprehensive Structure of **NXxlaue**


=====================  ========  =========  ===================================
Name and Attributes    Type      Units      Description (and Occurrences)
=====================  ========  =========  ===================================
class                  ..        ..         ..
=====================  ========  =========  ===================================
        