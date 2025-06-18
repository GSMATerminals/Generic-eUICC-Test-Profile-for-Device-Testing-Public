# Generic-eUICC-Test-Profile-for-Device-Testing-Public
The introduction of Devices with non-removable UICC presents a need to review best practice for testing. System simulator-based 
Device testing for industry certification schemes such as GCF and PTCRB has traditionally expected the necessary test profiles
to be made available via removable test UICCs. As industry moves towards non-removable (embedded) UICC, the common way of testing
Devices becomes less clear. The opportunity therefore exists to normalize the way in which Test Profiles for embedded UICCs will be
available, and configurable, for industry standardised testing.


This document and file are provided by the GSMA for information and third party internal use only.
The GSMA cannot be held accountable for the use of the document or file.
It is provided “as is” without any warranty or liability attached.


GSMA TS48 eSIM GTP V1.0 Release info: This version has been deprecated

Both the asn.1 Profiles are compliant with the SIMalliance Interoperable Profile v2.1 and both of them are implementing the content of the excel file that is part of TS.48.
The reason to have two asn.1 files is related to a different interpretation of the SIMalliance Interoperable Profile specification concerning the handling of a PIN PE.
Compare to GSMA_TS48_eSIM_GTP_Profile_Package_v1A, GSMA_TS48_eSIM_GTP_Profile_Package_v1B adds the selection of DF Telecom for PIN creation.
Both of them are a valid representation of the excel file and any EUM may choose one or the other to be used on its eUICC products.
Future version of this specification will solve this Profiles duality with the reference of SIMalliance Interoperable Profile v2.2 in which all identified different interpretations have been solved.

GSMA TS48 eSIM GTP V2.0 Release info: This version has been deprecated

GSMA TSG is pleased to announce the publication of V2.0 of the TS.48 ‘Generic eUICC Test Profile for Device Testing’ which defines an eSIM test profile for use in testing product with System Simulators, typically for use when testing a device with a non-removable eSIM to ensure  compliance to 3GPP specifications..

TS.48 V2.0 now includes the required profile content to allow running of 5G SA test cases and also V2X test cases, for both SIM Alliance v2.1 and 2.3 speciation’s.

Please note: Four reference  ASN.1 Files are available with and without the V2X capability, for both SIM Alliance 2.1 and 2.3

TS.48 V3.0 takes account of feedback that we received, and ensures this specification is now compliant to 3GPP TS 31.102 Release 15 v15.9.0, specifically noting the EF-NSI is not compatible with this release. This version has been deprecated

TS.48 v1 to v6 have been deprecated.
Please ONLY use verion TS.48 v7.0
