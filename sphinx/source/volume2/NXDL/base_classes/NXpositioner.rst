..  _NXpositioner:

############
NXpositioner
############

.. index::  ! . NXDL base_classes; NXpositioner

category:
    base_classes

NXDL source:
    NXpositioner
    
    (http://svn.nexusformat.org/definitions/trunk/base_classes/NXpositioner.nxdl.xml)

version:
    1.0

SVN Id:
    $Id$

extends class:
    :ref:`NXobject`

other classes included:
    none

symbol list:
    none

documentation:
    This group describes a generic positioner
    such as a motor or piezo-electric transducer.  It is used to document the
    current information of a piece of beam line equipment.
    Note: When using multiple NXpositioner groups, it is suggested to place
    them inside a NXcollection group.  In such cases, when
    NXpositioner is used in another class,
    NXcollection/NXpositioner
    is then constructed.
    


.. rubric:: Basic Structure of **NXpositioner**

::

    NXpositioner (base class, version 1.0)
      acceleration_time:NX_NUMBER
      controller_record:NX_CHAR
      description:NX_CHAR
      name:NX_CHAR
      raw_value:NX_NUMBER[n]
      soft_limit_max:NX_NUMBER
      soft_limit_min:NX_NUMBER
      target_value:NX_NUMBER[n]
      tolerance:NX_NUMBER[n]
      value:NX_NUMBER[n]
      velocity:NX_NUMBER
    

.. rubric:: Comprehensive Structure of **NXpositioner**


=====================  ========  =========  ===================================
Name and Attributes    Type      Units      Description (and Occurrences)
=====================  ========  =========  ===================================
class                  ..        ..         ..
=====================  ========  =========  ===================================
        