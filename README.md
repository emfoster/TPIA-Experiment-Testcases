# File Format
The file formats presented here are .glm files used in Pacific Northwest National Laboratory's (PNNL) open source distribution analysis tool GridLAB-D. 
If you are unfamiliar with .glm files, you can use the National Renewable Energy Lab's open source tool DiTTo to convert .glm files to other formats, 
including CYME or OPEN-DSS file formats. An explanation of using DiTTo to convert file formats can be found here: https://nrel.github.io/ditto/cli-examples/

All of the modified testcases presented here are overloaded versions of the original, denoted by the "OV" at the end of the file name. 

# Taxonomy Feeders
The RX-XX.XX-X format testcases are taxonomy feeders created by PNNL. You can find in-depth descriptions of these cases including information on the type and amount of equipment in the testcase in [1]

Testcase Name  | System Voltage | PNNL Description [1]  | Modifications
------------------  | -------------- | --------------------- | -------------
R1-12.47-1     |    12.47 kV    | moderate suburban/rural area   | no network modifications; control parameters turned off
R1-12.47-3_OV     |    12.47 kV    | moderate urban area   | some loads were modified by a factor of 5 and DERs were added
R2-25.00-1_OV     |     24.9 kV    | moderate suburban area| network is the same; some loads were modified by a factor of 2.9
R3-12.47-3     |    12.47 kV    | heavy suburban area   | no network modifications; control parameters turned off
R3-12.47-3_OV     |    12.47 kV    | heavy suburban area   | network is the same; some loads were modified by a factor of 3.865
R4-12.47-1_EV    |    12.47 kV    | heavy urban area      | In the EV testcase, the network is the same and some loads were modified by a factor of 4
R4-12.47-1    |    12.47 kV    | heavy urban area      | no network modifications; control parameters turned off

# IEEE Testcase
Base Testcase Name  | System Voltage  | Modifications
------------------  | --------------  | -------------
8500node            |    7.2kV        | network is the same; some loads were modified by a factor of 2.63

# References
[1] K.P. Schneider, Y. Chen, D. P. Chassin, R. G. Pratt, D. W. Engel, and S. E. Thompson, _Modern Grid Initiative Distribution Taxonomy Final Report_, Pacific Northwest National Lab, Richland, WA, Nov. 2008.
