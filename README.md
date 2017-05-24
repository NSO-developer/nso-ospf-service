# nso-ospf-service
Service that deploys OSPF on a device
## Description
A Cisco NSO service package for managing the ospf configuration on a device.  Conceived for a campus network use case where this service was a sub-service as part of a stacked service.  This service service can be used standalone or as part of a [stack service](http://linktoNSOdocs/ncs.development.services.stacked_services.html "NSO Stack Service Documentation").
## Dependenies
* NSO 4.3 - Minimum Version
* cisco-ios NED
## Installation
Clone this package into your NSO server's or project's packages directory.  If using a newer version of NSO the package can be recompiled by issuing the following command:

`<NSO Server or Project directory>/packages/nso-ospf-service/src/make all`
