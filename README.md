* NeXus: http://www.nexusformat.org/
* documentation: http://download.nexusformat.org/doc/html/index.html


These are the components that define the structure of NeXus data files in the development directory.

        BASE.xsd                    used to validate NeXus data files, defines NXroot
        LGPL.txt                    one proposed license model
        NeXus.xsd                   used to validate NeXus data files
        README.txt                  README file
        applications/               NXDL files for applications and instrument defs
        base_classes/               NXDL files for components
        contributed_definitions/    NXDL files from the community
        manual/                     Sphinx source files for the NeXus documentation
        nxdl.xsd                    XML Schema for NXDL files
        nxdlTypes.xsd               called by nxdl.xsd
        schema/                     schema files created from NXDL sources
        sphinx/                     remnant Sphinx source files for the manual (pre-release development)
        test/                       data and examples
        utils/                      various tools used in the definitions tree
        www/                        launch (home) page of NeXus WWW site
        xslt/                       various XML stylesheet transformations

See README.cmake.txt for building instructions


[![Join the chat at https://gitter.im/canSAS-org/NXcanSAS](https://badges.gitter.im/canSAS-org/NXcanSAS.svg)](https://gitter.im/canSAS-org/NXcanSAS?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)