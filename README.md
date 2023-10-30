# Security Control Mappings

This repository aims to collect existing mappings of cyber security controls. 
Two type of mappings are included, both to [MITRE ATT&CK's](https://attack.mitre.org/) TTPs and to controls from other frameworks.
Both types are presented in their respective folders, where the original source mappings are included.

These mappings can be used to understand the relationships between various security controls and between security controls and attack techniques. Some creators tried to create their mappings in such a way that implementing one control will contribute to implementing the other, like CIS.
NIST denotes that one should not assume there is a one-to-one relationship between controls, some controls might not be equal and implement either a subset or a superset of the other control.
For this reason, CIS has specified the mapping relationship in their documents.

## Collected direct mappings

### MITRE ATT&CK TTP - Control Mappings

| Control Set           | MITRE ATT&CK Version | File | Reference                                                                               | Comments |
|-----------------------|----------------------|------|-----------------------------------------------------------------------------------------|----------|
| NIST SP 800-53 rev. 5 | 12.1                 | [file](./TTP%20-%20Control/source%20material/nist800-53-r5-mappings-attckv12.xlsx)     | <https://github.com/center-for-threat-informed-defense/attack-control-framework-mappings> |          |
| CIS Controls v8       | 8.2                  |[file](./TTP%20-%20Control/source%20material/CIS_Controls_v8_ATTCKv82_condensed.xlsx)      | <https://www.cisecurity.org/controls/cis-controls-navigator>    | Exported from CIS Controls Navigator         |
| CIS Controls v7.1     | 8.2                  |[file](./TTP%20-%20Control/source%20material/CIS_Controls_v7.1_ATTCKv82_condensed.xlsx)     | <https://www.cisecurity.org/controls/cis-controls-navigator>    | Exported from CIS Controls Navigator         |

### Control - Control Mappings

| Control set A         | Control set B          | File | Reference                                                                                           | Comments |
|-----------------------|------------------------|------|-----------------------------------------------------------------------------------------------------|----------|
| NIST SP 800-53 rev. 5 | ISO/IEC 27001:2013         |[file](./Control%20-%20Control/source%20material/sp800-53r5-to-iso-27001.2013-mapping.docx)| <https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final>                                                  |          |
| NIST SP 800-53 rev. 5 | ISO/IEC 27001:2022         |[file](./Control%20-%20Control/source%20material/sp800-53r5-to-iso-27001-mapping.xlsx)| <https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final>                                                  |          |
| NIST SP 800-53 rev. 5 | NIST CSF V1.1          |[file](./Control%20-%20Control/source%20material/csf-pf-to-sp800-53r5-mappings.xlsx) | <https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final>                                                  |          |
| NIST SP 800-53 rev. 5 | NIST Privacy Framework |[file](./Control%20-%20Control/source%20material/csf-pf-to-sp800-53r5-mappings.xlsx)| <https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final>                                                  |          |
| CIS Controls v8       | ISO/IEC 27001:2022         |[file](./Control%20-%20Control/source%20material/CIS_Controls_v8_NEW_MAPPING_to_ISO.IEC_27001.2022_2_2023.xlsx)      | <https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-iso-iec2-27002-2022>     |          |
| CIS Controls v8       | NIST SP 800-53 rev.5   |[file](./Control%20-%20Control/source%20material/CIS_Controls_v8_Mapping_to_NIST_SP_800_53_Rev_5_Moderate_and_Low_Base.xlsx)      | <https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-800-53-rev-5>       |          |
| CIS Controls V8       | NIST CSF               |[file](./Control%20-%20Control/source%20material/CIS_Controls_v8_Mapping_to_NIST_CSF_2_2023.xlsx)     | <https://www.cisecurity.org/insights/white-papers/cis-controls-v8-mapping-to-nist-csf>                |          |
| CIS Controls V7.1     | ISO/IEC 27001:2013         |[file](./Control%20-%20Control/source%20material/CIS_Controls_v7.1_Mapping_to_ISO_27001_v19.07.xlsx)      | <https://www.cisecurity.org/insights/white-papers/cis-controls-and-sub-controls-mapping-to-iso-27001> |          |
| NIS2                  | ISO/IEC 27001:2022         | X | <https://www.huntandhackett.com/blog/iso-mapping-tool>  | |
| NIS2                  | CIS Controls V8        | X | <https://www.huntandhackett.com/blog/mapping-tool>  | |

## Altered and combined mappings

I've altered the spreadsheet to a standard format and kept only the mappings themselves. This way they can be interpreted better by (custom) parsers and/or tooling.
There are also new mappings created by combining the existing direct mappings from above.

At the moment I am not sure if I can publicly share these altered mappings, might come soon.

## Useful Resources

The [CIS Critical Security Controls Navigator](https://www.cisecurity.org/controls/cis-controls-navigator) is a free tool with a dynamic list of the CIS Safeguards that can be filtered by Implementation Groups and **mappings to multiple frameworks**.

[NIS2 Mappings to CIS](https://www.huntandhackett.com/blog/mapping-tool)
[NIS2 Mappings to ISO/IEC 27001:2022](https://www.huntandhackett.com/blog/iso-mapping-tool)
