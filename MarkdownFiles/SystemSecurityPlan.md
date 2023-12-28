# System Security Plan

## Background

The Federal Information Processing Standard (FIPS) 200, Minimum Security Requirements for Federal Information and Information Systems, specifies minimum security requirements for information systems in seventeen areas. Minimum security requirements in these seventeen areas are met through the use of security controls outlined in NIST Special Publication 800-53. These controls are documented within this system security plan.

The Federal Information Security Management Act (FISMA) requires compliance with minimum security requirements identified in FIPS 200, and the development of a formal system security plan (SSP). Compliance with FIPS 200 is required for information systems within the federal government, and optionally available for use on systems outside of the federal government.

A system security plan (SSP) should be complete prior to accreditation of a system and placing it in production. An SSP is also a living document, which should be updated and routinely reviewed. A plan of action and milestones (POAM) should accompany the SSP. The accrediting official reviews the SSP and POAM, and assesses the risks when authorizing or denying the accreditation of a system.

## System Security Plan

1. **Information System Name:** Standalone System

2. **Information System Categorization (NIST SP 800-60, Volumes 1 & 2):** LOW.

```text
SC personal information = {(confidentiality, LOW), (integrity, LOW), (availability, LOW)}
```

Potential impact is low since the loss of confidentiality, integrity, or availability would have limited adverse effects on the users and organization, including minor to no damage to personal assets  financial loss, and minor to no harm to individuals.


3. **Information System Owner:** Mr. System Owner

4. **Authorizing Official:** Mr. Authorizing Official

5. **Other Designated Contacts:** N/A

6. **Assignment of Security Responsibility:**

	a. Information System Security Manager: Mr. ISSM

	b. Information System Security Officer: Mr. ISSO

	c. System Administrator: Mr. SysAdmin

7. **Information System Operational Status:** Development

8. **Information System Type:** General Support System

9. **General system Description/Purpose:**
	
    This standalone system is used for receiving media from public agencies outside of the Air Force. This media contains data that is UNCLASSIFIED, and it does not process PII, PHI, or Controlled Unclassified Information (CUI). Data types processed on this system include Microsoft Word and Excel documents, as well as Adobe PDF files.

10. **System Environment:**
	
    The system is a single laptop that is disconnected from any network connections. Wireless connections and bluetooth connections are disabled, and all peripherals are connected via wires. The system physically resides within a vindicated building located inside a controlled military installation.
    
    Operating Systems: 
    * Windows 11 Professional Edition (64-bit)
    
    Applications: 
    * None

11. **System Interconnections/Information Sharing:** N/A

12. **Related Laws/Regulations/Policies:**
   
    * Federal Information Security Management Act (FISMA)
    * NIST SP 800-37: Risk Management Framework

13. **Minimum Security Controls:** [Security Controls Baseline (LOW)](../Artifacts/ControlsBaselineLOW.csv)

14. **Information System Security Plan Completion Date:**

15. **Information System Security Plan Approval Date:**

