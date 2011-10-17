..  _NXbeam_stop:

###########
NXbeam_stop
###########

.. index::  ! . NXDL base_classes; NXbeam_stop

category:
    base_classes

NXDL source:
    NXbeam_stop
    
    (http://svn.nexusformat.org/definitions/trunk/base_classes/NXbeam_stop.nxdl.xml)

version:
    1.0

SVN Id:
    $Id$

extends class:
    :ref:`NXobject`

other classes included:
    :ref:`NXgeometry`

symbol list:
    none

documentation:
    A class for a beamstop. Beamstops and their positions are important for SANS
    and SAXS experiments.
    


.. rubric:: Basic Structure of **NXbeam_stop**

::

    NXbeam_stop (base class, version 1.0)
      description:NX_CHAR
      distance_to_detector:NX_FLOAT
      size:NX_FLOAT
      status:NX_CHAR
      x:NX_FLOAT
      y:NX_FLOAT
      NXgeometry
    

.. rubric:: Comprehensive Structure of **NXbeam_stop**


=====================  ========  =========  ===================================
Name and Attributes    Type      Units      Description (and Occurrences)
=====================  ========  =========  ===================================
class                  ..        ..         ..
=====================  ========  =========  ===================================
        