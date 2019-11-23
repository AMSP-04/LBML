# Low Level BML FOM Module

## Purpose
The NETN-LBML FOM module is simulation oriented and focuses on tasks with a fine granularity:
* It helps the simulation in understanding the C-BML message and it also introduces some concepts about "Command & Control" that simulations could use between themselves (for example during the disaggregation process).
* It contains compact low level-tasks and commands that can easily be interpreted and executed by CGF tools.
* It reflects the capabilities commonly found in COTS CGF tools, but it is independent of one specific COTS CGF tool and one specific agent framework or agent modelling paradigm.
* It is independent of any specific doctrine or tactics.
* It defines status reports needed for the agent decision making and for producing C-BML reports.

			
## Licence

Copyright (C) 2019 NATO/OTAN.
This work is licensed under a [Creative Commons Attribution-NoDerivatives 4.0 International License](LICENCE.md). 

The work includes the [NETN-LBML](NETN-LBML_v1.1.0.xml) FOM Module.

Above licence gives you the right to use and redistribute the NETN FOM Module (XML file) in its entirety without modification. You are also allowed to develop new FOM Modules (in separate XML files and separate documentation) that build-on/extends the NETN module by reference and including necessary scaffolding classes. You are NOT allowed to modify this FOM Module without prior permission by the NATO Modelling and Simulation Group. 

## Versions, updates and extensions

All updates and versioning of this work is coordinated by the NATO Modelling and Simulation Coordination Office (MSCO), managed by the NATO Modelling and Simulation Group (NMSG) and performed as NATO Science and Technology Organization (STO) technical activities in support of the NMSG Modelling and Simulation Standards Subgroup (MS3).

Feedback on the use of this work, suggestions for improvements and identified issues are welcome and can be provided using GitHub issue tracking. To engage in the development and update of this FOM Module please contact your national NMSG representative.

Version numbering of this FOM Module and associated documentation is based on the following principles:

* New official version number is assigned and in effect only when a new release is made in the Master branch.
* Updates in the Develop branch will not change the version number.
* In the FOM Module `useHistory` information includes only information on official releases.
* Update of the major version number is made if the change constitutes a major restructuring, merging, addition or redefinition of semantics that breaks backward compatibility or cover entirely new concepts.
* Update of the minor version number is made if the change constitutes minor additions to existing concepts and editorial changes that do not break backward compatibility but may require updates of software to use new concepts.
* Patches are released to fix minor issues that do not break backward compatibility.

|Version|Description|
|---|---|
|v1.1.0 |NETN-LBML included in NETN FOM v2.0 as part of AMSP-04 Ed A.|

## Note

NETN-LBML will be deprecated on the release of NETN-ETR as part of NETN-FOM v3.0 which is currently under development.

## Documentation

[Full Documentation](https://nso.nato.int/nso/nsdd/APdetails.html?APNo=2268&LA=EN)
