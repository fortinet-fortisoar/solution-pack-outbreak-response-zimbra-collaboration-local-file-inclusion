# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 

# Overview 

A Local File Inclusion (LFI) vulnerability (CVE-2025-68645) exists in the Zimbra Collaboration Suite (ZCS) Webmail Classic UI due to improper handling of user-supplied request parameters in the RestFilter servlet. An unauthenticated remote attacker can craft malicious requests, potentially exposing sensitive configuration and application data and aiding further compromise. 

 The **Outbreak Response - Zimbra Collaboration Local File Inclusion** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/2.3.0/docs/background-information.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*.

 The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/zimbra-collaboration-lfi) contains information about the outbreak alert **Outbreak Response - Zimbra Collaboration Local File Inclusion**. 

## Background: 

Successful exploitation may allow threat actors to:
• Leak sensitive files from the system WebRoot directory
• Gain reconnaissance and foothold inside the targeted environment.
• Potentially leverage exposed information for further exploitation or escalation.
• A public proof-of-concept exploit is available, and active exploitation has been observed. 

## Announced: 

Apply vendor patches immediately for all affected ZCS versions (Zimbra Collaboration (ZCS) 10.0 -10.0.17- Zimbra Collaboration (ZCS) 10.1.0 - 10.1.12), and Fixed versions are 10.0.18 and 10.1.13. 

## Latest Developments: 

January 28, 2026: FortiGuard released a Threat Signal Report.
https://www.fortiguard.com/threat-signal-report/6324/zimbra-collaboration-local-file-inclusion

January 23, 2026: CISA has confirmed active exploitation by adding the vulnerability to its Known Exploited Vulnerabilities (KEV) Catalog.

November 6, 2025: Zimbra Patch Release.
https://wiki.zimbra.com/wiki/Zimbra_Releases/10.0.18#Security_Fixes 

# Next Steps
 | [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) | 
 |--------------------------------------------|----------------------------------------------|------------------------|------------------------------|
