# Building Device and Asset Naming Standards initiative

Status: *release 1.0.0*

This repository holds resources for an initiative to improve interoperability in building management, by focusing on standardising naming of building devices and assets.

Achieving a common standard across building devices’ naming is an important first step towards being able to efficiently collect, analyse and capture data insights from buildings, and thus optimise building performance to reduce the operational cost and environmental impact of managing buildings.

Longer-term, this sets the groundwork for real industry collaboration - with the potential to create industry-wide benchmarking, and to facilitate trading of buildings between portfolios.

A naming and labelling standard (complementing other industry initiatives ) will simplify and drive consistency, thus increasing value by unlocking the application of technologies such as machine learning.  

The work of this community group aligns with and complements other initiatives in the industry such as:

* [IFC](https://technical.buildingsmart.org/standards/ifc/ifc-schema-specifications/)
* [Uniclass](https://www.thenbs.com/our-tools/uniclass-2015) and [Uniclass2](http://www.cpic.org.uk/uniclass2/)
* [Omniclass](https://www.csiresources.org/standards/omniclass)
* [CIBSE Symbols](https://www.cibse.org/knowledge/digital-knowledge-tools/symbols)
* [UDMI](https://github.com/faucetsdn/udmi)
* [Web of Things](https://www.w3.org/WoT/)
* [HyperCat](https://hypercatiot.github.io/)
* [Project Haystack](https://project-haystack.org/)
* [Brick Schema](https://brickschema.org/)
* [Digital Buildings Ontology](https://github.com/google/digitalbuildings)

In scope for this work are:
- A [specification for naming syntax](BDNS_Specification_naming_syntax.md)
- A [register of building device type abbreviations](BDNS_Abbreviations_Register.csv)

## Use

The device and asset names defined in this standard are meant to be used in the following applications:

* naming of CAD object instances in drawings
* naming of object instances in BIM models
* naming of control devices in control software (for instance BACnet device names)
* naming of assets in asset management systems
* naming of devices in IoT ingestion systems
* naming of devices and assets in databases
* naming of devices and assets in MQTT topics

## Note

At the moment of release 1.0, the standard is primarily focusing on naming of building control devices.

With time, it will also include maintainable asset names.
