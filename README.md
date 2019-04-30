# Generic-eUICC-Test-Profile-for-Device-Testing-Public
The introduction of Devices with non-removable UICC presents a need to review best practice for testing. System simulator-based 
Device testing for industry certification schemes such as GCF and PTCRB has traditionally expected the necessary test profiles
to be made available via removable test UICCs. As industry moves towards non-removable (embedded) UICC, the common way of testing
Devices becomes less clear. The opportunity therefore exists to normalize the way in which Test Profiles for embedded UICCs will be
available, and configurable, for industry standardised testing.


This document and file are provided by the GSMA for information and third party internal use only.
The GSMA cannot be held accountable for the use of the document or file.
It is provided “as is” without any warranty or liability attached.


GSMA TS48 eSIM GTP V1.0 Release info:

Both the asn.1 Profiles are compliant with the SIMalliance Interoperable Profile v2.1 and both of them are implementing the content of the excel file that is part of TS.48.
The reason to have two asn.1 files is related to a different interpretation of the SIMalliance Interoperable Profile specification concerning the handling of a PIN PE.
Compare to GSMA_TS48_eSIM_GTP_Profile_Package_v1A, GSMA_TS48_eSIM_GTP_Profile_Package_v1B adds the selection of DF Telecom for PIN creation.
Both of them are a valid representation of the excel file and any EUM may choose one or the other to be used on its eUICC products.
Future version of this specification will solve this Profiles duality with the reference of SIMalliance Interoperable Profile v2.2 in which all identified different interpretations have been solved.

