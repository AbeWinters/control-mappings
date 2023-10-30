# Security Control Mappings

This repository aims to collect existing mappings of cyber security controls. 
Two type of mappings are included, both to [MITRE ATT&CK's](https://attack.mitre.org/) TTPs and to controls from other frameworks.
Both types are presented in their respective folders, where the original source mappings are included.

These mappings can be used to understand the relationships between various security controls and between security controls and attack techniques. Some creators tried to create their mappings in such a way that implementing one control will contribute to implementing the other, like CIS.
NIST denotes that one should not assume there is a one-to-one relationship between controls, some controls might not be equal and implement either a subset or a superset of the other control.
For this reason, CIS has specified the mapping relationship in their documents.

## Orginal existing mappings

### TTP - Control Mappings
| Control Set           | MITRE ATT&CK Version | File | Reference                                                                               | Comments |
|-----------------------|----------------------|------|-----------------------------------------------------------------------------------------|----------|
| NIST SP 800-53 rev. 5 | 12.1                 |      | https://github.com/center-for-threat-informed-defense/attack-control-framework-mappings |          |
| CIS Controls v8       | 8.2                  |      | https://www.cisecurity.org/controls/cis-controls-navigator                              |          |
| CIS Controls v7.1     | 8.2                  |      | https://www.cisecurity.org/controls/cis-controls-navigator                              |          |

### Control - Control Mappings
| Control set A         | Control set B          | File | Reference                                                                                           | Comments |
|-----------------------|------------------------|------|-----------------------------------------------------------------------------------------------------|----------|
| NIST SP 800-53 rev. 5 | ISO 27001:2013         |      | https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final                                                  |          |
| NIST SP 800-53 rev. 5 | ISO 27001:2022         |      | https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final                                                  |          |
| NIST SP 800-53 rev. 5 | NIST CSF V1.1          |      | https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final                                                  |          |
| NIST SP 800-53 rev. 5 | NIST Privacy Framework |      | https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final                                                  |          |
| CIS Controls v8       | ISO 27001:2022         |      | https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-iso-iec2-27002-2022     |          |
| CIS Controls v8       | NIST SP 800-53 rev.5   |      | https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-800-53-rev-5       |          |
| CIS Controls V8       | NIST CSF               |      | https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-csf                |          |
| CIS Controls V7.1     | ISO 27001:2013         |      | https://www.cisecurity.org/insights/white-papers/cis-controls-and-sub-controls-mapping-to-iso-27001 |          |

## Useful Resources

The [CIS Critical Security Controls Navigator](https://www.cisecurity.org/controls/cis-controls-navigator) is a free tool with a dynamic list of the CIS Safeguards that can be filtered by Implementation Groups and **mappings to multiple frameworks**.

## Previous overview

### NIST SP 800-53 rev. 5 -> MITRE ATT&CK

Original file: [nist800-53-r5-mappings.xlsx](./nist800-53-r5-mappings.xlsx)

Source: [MITRE CTID](https://github.com/center-for-threat-informed-defense/attack-control-framework-mappings)

### NIST SP 800-53 rev. 5 -> ISO 27001:2013

Original file: [sp800-53r5-to-iso-27001-mapping.docx](./sp800-53r5-to-iso-27001-mapping.docx)

Edited to Excel: [sp800-53r5-to-iso-27001-mapping.xlsx](./sp800-53r5-to-iso-27001-mapping.xlsx)

Source: [NIST SP 800-53 rev. 5 publication](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

### NIST Cybersecurity Framework (CSF) V1.1 -> NIST SP 800-53 rev. 5 

Original file: [csf-pf-to-sp800-53r5-mappings.xlsx](./csf-pf-to-sp800-53r5-mappings.xlsx)

Source: [NIST SP 800-53 rev. 5 publication](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)

### CIS Controls v8 -> ISO/IEC 27001:2022

Original file [CIS_Controls_v8_NEW_MAPPING_to_ISO.IEC_27001.2022_2_2023.xlsx](./CIS_Controls_v8_NEW_MAPPING_to_ISO.IEC_27001.2022_2_2023.xlsx)

Source: [Center for Internet Security](https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-iso-iec-27001-2022)

### CIS Controls v8 -> NIST SP 800-53 rev. 5

Original file: [CIS_Controls_v8_Mapping_to_NIST_SP_800_53_Rev_5_Moderate_and_Low_Base.xlsx](./CIS_Controls_v8_Mapping_to_NIST_SP_800_53_Rev_5_Moderate_and_Low_Base.xlsx)

Source: [Center for Internet Security](https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-800-53-rev-5)
