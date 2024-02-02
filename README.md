# OpenTimelineIO FCP X XML Adapter
[![Build Status](https://github.com/OpenTimelineIO/otio-fcpx-xml-adapter/actions/workflows/ci.yaml/badge.svg)](https://github.com/OpenTimelineIO/otio-fcpx-xml-adapter/actions/workflows/ci.yaml)
![Dynamic YAML Badge](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2FOpenTimelineIO%2Fotio-fcpx-xml-adapter%2Fmain%2F.github%2Fworkflows%2Fci.yaml&query=%24.jobs%5B%22test-plugin%22%5D.strategy.matrix%5B%22otio-version%22%5D&label=OpenTimelineIO)
![Dynamic YAML Badge](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2FOpenTimelineIO%2Fotio-fcpx-xml-adapter%2Fmain%2F.github%2Fworkflows%2Fci.yaml&query=%24.jobs%5B%22test-plugin%22%5D.strategy.matrix%5B%22python-version%22%5D&label=Python)

The `fcpx_xml` adapter is part of OpenTimelineIO's contrib adapter plugins.
It provides reading and writing of Final Cut Pro X formatted XML files. 
For more information on the FCP X XML format please check the links in the 
[reference](#fcpx-xml-references) section 

# Adapter Feature Matrix

The following features of OTIO are supported by the `fcpx_xml` adapter:

|Feature                  | Support |
|-------------------------|:-------:|
|Single Track of Clips    | ✔       |
|Multiple Video Tracks    | ✔       |
|Audio Tracks & Clips     | ✔       |
|Gap/Filler               | ✔       |
|Markers                  | ✔       |
|Nesting                  | ✔       |
|Transitions              | ✖       |
|Audio/Video Effects      | ✖       |
|Linear Speed Effects     | ✖       |
|Fancy Speed Effects      | ✖       |
|Color Decision List      | ✖       |
|Image Sequence Reference | ✖       |


# FCPX XML References

- [Reference](https://developer.apple.com/library/mac/documentation/FinalCutProX/Reference/FinalCutProXXMLFormat/Introduction/Introduction.html)

# License

OpenTimelineIO and the "fcpx xml" adapter are open source software.
Please see the [LICENSE](LICENSE) for details.

Nothing in the license file or this project grants any right to use Pixar or
any other contributor’s trade names, trademarks, service marks, or product names.

# Contributions

If you want to contribute to the project,
please see: https://opentimelineio.readthedocs.io/en/latest/tutorials/contributing.html  
Please also read up on [testing your code](https://github.com/OpenTimelineIO/otio-plugin-template#testing-your-plugin-during-development) 
in the "getting started" section of the OpenTimelineIO plugin template repository.

# Contact

For more information, please visit http://opentimeline.io/
or https://github.com/AcademySoftwareFoundation/OpenTimelineIO
or join our discussion forum: https://lists.aswf.io/g/otio-discussion
