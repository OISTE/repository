<img src="./media/media/image1.png"
style="width:1.67573in;height:1.67573in" />

**OISTE Foundation**

OISTE Global Trust Model

Certificate Policy (CP) for SSL Certificates

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 49%" />
</colgroup>
<thead>
<tr>
<th><strong>Date</strong>: 18/7/2024</th>
<th><strong>Version</strong>:</th>
</tr>
</thead>
<tbody>
<tr>
<td><strong>Status</strong>:</td>
<td><strong>No. Of Pages</strong>: 40</td>
</tr>
<tr>
<td><strong>OID</strong>:</td>
<td><strong>Classification</strong>:</td>
</tr>
<tr>
<td colspan="2"><strong>File</strong>: OGTM - CP SSL
Certificates.v1.6.docx</td>
</tr>
<tr>
<td colspan="2"><strong>Published by</strong>: OISTE Policy Approval
Authority</td>
</tr>
</tbody>
</table>

This document is issued by the OISTE Foundation, and licensed under a
**Creative Commons Attribution-NoDerivatives 4.0 (CC BY-ND 4.0)**

.

# Documentation management

# Document Approval

<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 43%" />
<col style="width: 45%" />
</colgroup>
<thead>
<tr>
<th>Version</th>
<th>PAA Representative #1</th>
<th>PAA Representative #2</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.6</td>
<td><p>Name:</p>
<p>Signature:</p></td>
<td><p>Name:</p>
<p>Signature:</p></td>
</tr>
</tbody>
</table>

# Version history

<table>
<colgroup>
<col style="width: 11%" />
<col style="width: 13%" />
<col style="width: 74%" />
</colgroup>
<thead>
<tr>
<th>Version</th>
<th>Date</th>
<th style="text-align: left;">Comments</th>
</tr>
</thead>
<tbody>
<tr>
<td>1.0</td>
<td>25/2/2019</td>
<td style="text-align: left;">First version</td>
</tr>
<tr>
<td>1.1</td>
<td>10/10/2020</td>
<td style="text-align: left;">Minor change to support DV certificates
without Subject contents</td>
</tr>
<tr>
<td>1.2</td>
<td>3/2/2021</td>
<td style="text-align: left;">Include mandate to disclose validation
sources</td>
</tr>
<tr>
<td>1.3</td>
<td>3/2/2022</td>
<td style="text-align: left;">Annual review. No changes.</td>
</tr>
<tr>
<td>1.4</td>
<td>30/1/2023</td>
<td style="text-align: left;">Annual review. No changes</td>
</tr>
<tr>
<td>1.5</td>
<td>24/1/2024</td>
<td style="text-align: left;">Annual review. No significant changes</td>
</tr>
<tr>
<td>1.6</td>
<td>18/7/2024</td>
<td style="text-align: left;">Annual review. No significant changes</td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
<tr>
<td></td>
<td></td>
<td style="text-align: left;"></td>
</tr>
</tbody>
</table>

**  
**

# Contents

[1 Introductions [9](#introductions)](#introductions)

[1.1 Overview [9](#overview)](#overview)

[1.1.1 The OGTM CP/CPS Documentation Framework
[10](#the-ogtm-cpcps-documentation-framework)](#the-ogtm-cpcps-documentation-framework)

[1.2 Document Name and Identification
[10](#document-name-and-identification)](#document-name-and-identification)

[1.3 PKI Participants [11](#pki-participants)](#pki-participants)

[1.3.1 Certification authorities
[11](#certification-authorities)](#certification-authorities)

[1.3.2 Registration authorities
[11](#registration-authorities)](#registration-authorities)

[1.3.3 Subscribers [11](#subscribers)](#subscribers)

[1.3.4 Relying parties [11](#relying-parties)](#relying-parties)

[1.3.5 Other participants
[11](#other-participants)](#other-participants)

[1.4 Certificate Usage [11](#certificate-usage)](#certificate-usage)

[1.4.1 Appropriate Certificate Uses
[11](#appropriate-certificate-uses)](#appropriate-certificate-uses)

[1.4.2 Prohibited certificate uses
[12](#prohibited-certificate-uses)](#prohibited-certificate-uses)

[1.5 Policy Administration
[12](#policy-administration)](#policy-administration)

[1.5.1 Organization administering the document
[12](#organization-administering-the-document)](#organization-administering-the-document)

[1.5.2 Contact Person (Contact Information)
[13](#contact-person-contact-information)](#contact-person-contact-information)

[1.5.3 Person determining CPS suitability for the policy
[13](#person-determining-cps-suitability-for-the-policy)](#person-determining-cps-suitability-for-the-policy)

[1.5.4 CPS approval procedures
[13](#cps-approval-procedures)](#cps-approval-procedures)

[1.6 Definitions and Acronyms
[13](#definitions-and-acronyms)](#definitions-and-acronyms)

[2 Publication and Repository Responsibilities
[14](#publication-and-repository-responsibilities)](#publication-and-repository-responsibilities)

[2.1 Repositories [14](#repositories)](#repositories)

[2.2 Publication [14](#publication)](#publication)

[2.3 Time or frequency of publication
[14](#time-or-frequency-of-publication)](#time-or-frequency-of-publication)

[2.4 Access control on repositories
[14](#access-control-on-repositories)](#access-control-on-repositories)

[3 Identification and Authentication
[15](#identification-and-authentication)](#identification-and-authentication)

[3.1 Naming [15](#naming)](#naming)

[3.1.1 Types of names [15](#types-of-names)](#types-of-names)

[3.1.2 Need for names to be meaningful
[15](#need-for-names-to-be-meaningful)](#need-for-names-to-be-meaningful)

[3.1.3 Anonymity of subscribers and pseudonyms
[15](#anonymity-of-subscribers-and-pseudonyms)](#anonymity-of-subscribers-and-pseudonyms)

[3.1.4 Rules for interpreting various name forms
[15](#rules-for-interpreting-various-name-forms)](#rules-for-interpreting-various-name-forms)

[3.1.5 Uniqueness of names
[15](#uniqueness-of-names)](#uniqueness-of-names)

[3.1.6 Recognition, authentication, and role of trademarks
[15](#recognition-authentication-and-role-of-trademarks)](#recognition-authentication-and-role-of-trademarks)

[3.2 Initial Identity Validation
[15](#initial-identity-validation)](#initial-identity-validation)

[3.2.1 Method to prove possession of private key
[16](#method-to-prove-possession-of-private-key)](#method-to-prove-possession-of-private-key)

[3.2.2 Authentication of organization identity
[16](#authentication-of-organization-identity)](#authentication-of-organization-identity)

[3.2.3 Authentication of individual identity
[16](#authentication-of-individual-identity)](#authentication-of-individual-identity)

[3.2.4 Non-verified subscriber information
[16](#non-verified-subscriber-information)](#non-verified-subscriber-information)

[3.2.5 Validation of authority
[17](#validation-of-authority)](#validation-of-authority)

[3.2.6 Criteria for interoperation
[17](#criteria-for-interoperation)](#criteria-for-interoperation)

[3.3 Identification and Authentication for Re-key Requests
[17](#identification-and-authentication-for-re-key-requests)](#identification-and-authentication-for-re-key-requests)

[3.3.1 Identification and authentication for routine re-key
[17](#identification-and-authentication-for-routine-re-key)](#identification-and-authentication-for-routine-re-key)

[3.3.2 Identification and authentication for re-key after revocation
[17](#identification-and-authentication-for-re-key-after-revocation)](#identification-and-authentication-for-re-key-after-revocation)

[3.4 Identification and Authentication for Revocation Requests
[17](#identification-and-authentication-for-revocation-requests)](#identification-and-authentication-for-revocation-requests)

[4 Certificate Life-Cycle Operational Requirements
[18](#certificate-life-cycle-operational-requirements)](#certificate-life-cycle-operational-requirements)

[4.1 Certificate Application
[18](#certificate-application)](#certificate-application)

[4.1.1 Who can submit a certificate application
[18](#who-can-submit-a-certificate-application)](#who-can-submit-a-certificate-application)

[4.1.2 Enrolment process and responsibilities
[18](#enrolment-process-and-responsibilities)](#enrolment-process-and-responsibilities)

[4.2 Certificate Application Processing
[18](#certificate-application-processing)](#certificate-application-processing)

[4.2.1 Performing identification and authentication functions
[18](#performing-identification-and-authentication-functions)](#performing-identification-and-authentication-functions)

[4.2.2 Approval or rejection of certificate applications
[18](#approval-or-rejection-of-certificate-applications)](#approval-or-rejection-of-certificate-applications)

[4.2.3 Time to process certificate applications
[18](#time-to-process-certificate-applications)](#time-to-process-certificate-applications)

[4.3 Certificate Issuance
[19](#certificate-issuance)](#certificate-issuance)

[4.3.1 CA actions during certificate issuance
[19](#ca-actions-during-certificate-issuance)](#ca-actions-during-certificate-issuance)

[4.3.2 Notifications to subscriber by the CA of issuance of certificate
[19](#notifications-to-subscriber-by-the-ca-of-issuance-of-certificate)](#notifications-to-subscriber-by-the-ca-of-issuance-of-certificate)

[4.4 Certificate Acceptance
[19](#certificate-acceptance)](#certificate-acceptance)

[4.4.1 Conduct constituting certificate acceptance
[19](#conduct-constituting-certificate-acceptance)](#conduct-constituting-certificate-acceptance)

[4.4.2 Publication of the certificate by the CA
[19](#publication-of-the-certificate-by-the-ca)](#publication-of-the-certificate-by-the-ca)

[4.4.3 Notification of certificate issuance by the CA to other entities
[19](#notification-of-certificate-issuance-by-the-ca-to-other-entities)](#notification-of-certificate-issuance-by-the-ca-to-other-entities)

[4.5 Key Pair and Certificate Usage
[19](#key-pair-and-certificate-usage)](#key-pair-and-certificate-usage)

[4.5.1 Subscriber private key and certificate usage
[19](#subscriber-private-key-and-certificate-usage)](#subscriber-private-key-and-certificate-usage)

[4.5.2 Relying party public key and certificate usage
[19](#relying-party-public-key-and-certificate-usage)](#relying-party-public-key-and-certificate-usage)

[4.6 Certificate Renewal
[19](#certificate-renewal)](#certificate-renewal)

[4.6.1 Circumstance for certificate renewal
[20](#circumstance-for-certificate-renewal)](#circumstance-for-certificate-renewal)

[4.6.2 Who may request renewal
[20](#who-may-request-renewal)](#who-may-request-renewal)

[4.6.3 Processing certificate renewal requests
[20](#processing-certificate-renewal-requests)](#processing-certificate-renewal-requests)

[4.6.4 Notification of new certificate issuance to subscriber
[20](#notification-of-new-certificate-issuance-to-subscriber)](#notification-of-new-certificate-issuance-to-subscriber)

[4.6.5 Conduct constituting acceptance of a renewal certificate
[20](#conduct-constituting-acceptance-of-a-renewal-certificate)](#conduct-constituting-acceptance-of-a-renewal-certificate)

[4.6.6 Publication of the renewal certificate by the CA
[20](#publication-of-the-renewal-certificate-by-the-ca)](#publication-of-the-renewal-certificate-by-the-ca)

[4.6.7 Notification of certificate issuance by the CA to other entities
[20](#notification-of-certificate-issuance-by-the-ca-to-other-entities-1)](#notification-of-certificate-issuance-by-the-ca-to-other-entities-1)

[4.7 Certificate Re-key [20](#certificate-re-key)](#certificate-re-key)

[4.7.1 Circumstance for certificate re-key
[20](#circumstance-for-certificate-re-key)](#circumstance-for-certificate-re-key)

[4.7.2 Who may request certification of a new public key
[20](#who-may-request-certification-of-a-new-public-key)](#who-may-request-certification-of-a-new-public-key)

[4.7.3 Processing certificate re-keying requests
[20](#processing-certificate-re-keying-requests)](#processing-certificate-re-keying-requests)

[4.7.4 Notification of new certificate issuance to subscriber
[20](#notification-of-new-certificate-issuance-to-subscriber-1)](#notification-of-new-certificate-issuance-to-subscriber-1)

[4.7.5 Conduct constituting acceptance of a re-keyed certificate
[20](#conduct-constituting-acceptance-of-a-re-keyed-certificate)](#conduct-constituting-acceptance-of-a-re-keyed-certificate)

[4.7.6 Publication of the re-keyed certificate by the CA
[21](#publication-of-the-re-keyed-certificate-by-the-ca)](#publication-of-the-re-keyed-certificate-by-the-ca)

[4.7.7 Notification of certificate issuance by the CA to other entities
[21](#notification-of-certificate-issuance-by-the-ca-to-other-entities-2)](#notification-of-certificate-issuance-by-the-ca-to-other-entities-2)

[4.8 Certificate Modification
[21](#certificate-modification)](#certificate-modification)

[4.8.1 Circumstance for certificate modification
[21](#circumstance-for-certificate-modification)](#circumstance-for-certificate-modification)

[4.8.2 Who may request certificate modification
[21](#who-may-request-certificate-modification)](#who-may-request-certificate-modification)

[4.8.3 Processing certificate modification requests
[21](#processing-certificate-modification-requests)](#processing-certificate-modification-requests)

[4.8.4 Notification of new certificate issuance to subscriber
[21](#notification-of-new-certificate-issuance-to-subscriber-2)](#notification-of-new-certificate-issuance-to-subscriber-2)

[4.8.5 Conduct constituting acceptance of modified certificate
[21](#conduct-constituting-acceptance-of-modified-certificate)](#conduct-constituting-acceptance-of-modified-certificate)

[4.8.6 Publication of the modified certificate by the CA
[21](#publication-of-the-modified-certificate-by-the-ca)](#publication-of-the-modified-certificate-by-the-ca)

[4.8.7 Notification of certificate issuance by the CA to other entities
[21](#notification-of-certificate-issuance-by-the-ca-to-other-entities-3)](#notification-of-certificate-issuance-by-the-ca-to-other-entities-3)

[4.9 Certificate Revocation and Suspension
[21](#certificate-revocation-and-suspension)](#certificate-revocation-and-suspension)

[4.9.1 Circumstances for revocation
[22](#circumstances-for-revocation)](#circumstances-for-revocation)

[4.9.2 Who can request revocation
[22](#who-can-request-revocation)](#who-can-request-revocation)

[4.9.3 Procedure for revocation request
[22](#procedure-for-revocation-request)](#procedure-for-revocation-request)

[4.9.4 Revocation request grace period
[22](#revocation-request-grace-period)](#revocation-request-grace-period)

[4.9.5 Time within which CA must process the revocation request
[22](#time-within-which-ca-must-process-the-revocation-request)](#time-within-which-ca-must-process-the-revocation-request)

[4.9.6 Revocation checking requirement for relying parties
[22](#revocation-checking-requirement-for-relying-parties)](#revocation-checking-requirement-for-relying-parties)

[4.9.7 CRL issuance frequency
[22](#crl-issuance-frequency)](#crl-issuance-frequency)

[4.9.8 Maximum latency for CRLs
[22](#maximum-latency-for-crls)](#maximum-latency-for-crls)

[4.9.9 On-line revocation/status checking availability
[22](#on-line-revocationstatus-checking-availability)](#on-line-revocationstatus-checking-availability)

[4.9.10 On-line revocation checking requirements
[22](#on-line-revocation-checking-requirements)](#on-line-revocation-checking-requirements)

[4.9.11 Other forms of revocation advertisements available
[22](#other-forms-of-revocation-advertisements-available)](#other-forms-of-revocation-advertisements-available)

[4.9.12 Special requirements regarding key compromise
[22](#special-requirements-regarding-key-compromise)](#special-requirements-regarding-key-compromise)

[4.9.13 Circumstances for suspension
[22](#circumstances-for-suspension)](#circumstances-for-suspension)

[4.9.14 Who can request suspension
[22](#who-can-request-suspension)](#who-can-request-suspension)

[4.9.15 Procedure for suspension request
[22](#procedure-for-suspension-request)](#procedure-for-suspension-request)

[4.9.16 Limits on suspension period
[23](#limits-on-suspension-period)](#limits-on-suspension-period)

[4.10 Certificate Status Services
[23](#certificate-status-services)](#certificate-status-services)

[4.10.1 Operational characteristics
[23](#operational-characteristics)](#operational-characteristics)

[4.10.2 Service availability
[23](#service-availability)](#service-availability)

[4.10.3 Optional features [23](#optional-features)](#optional-features)

[4.11 End of Subscription
[23](#end-of-subscription)](#end-of-subscription)

[4.12 Key Escrow and Recovery
[23](#key-escrow-and-recovery)](#key-escrow-and-recovery)

[4.12.1 Key escrow and recovery policy and practices
[23](#key-escrow-and-recovery-policy-and-practices)](#key-escrow-and-recovery-policy-and-practices)

[4.12.2 Session key encapsulation and recovery policy and practices
[23](#session-key-encapsulation-and-recovery-policy-and-practices)](#session-key-encapsulation-and-recovery-policy-and-practices)

[5 Management, Operational, and Physical Controls
[24](#management-operational-and-physical-controls)](#management-operational-and-physical-controls)

[5.1 Physical Security Controls
[24](#physical-security-controls)](#physical-security-controls)

[5.1.1 Site location and construction
[24](#site-location-and-construction)](#site-location-and-construction)

[5.1.2 Physical access [24](#physical-access)](#physical-access)

[5.1.3 Power and air conditioning
[24](#power-and-air-conditioning)](#power-and-air-conditioning)

[5.1.4 Water exposures [24](#water-exposures)](#water-exposures)

[5.1.5 Fire prevention and protection
[24](#fire-prevention-and-protection)](#fire-prevention-and-protection)

[5.1.6 Media storage [24](#media-storage)](#media-storage)

[5.1.7 Waste disposal [24](#waste-disposal)](#waste-disposal)

[5.1.8 Backup [24](#backup)](#backup)

[5.2 Procedural Controls
[24](#procedural-controls)](#procedural-controls)

[5.2.1 Trusted roles [24](#trusted-roles)](#trusted-roles)

[5.2.2 Number of persons required per task
[24](#number-of-persons-required-per-task)](#number-of-persons-required-per-task)

[5.2.3 Identification and authentication for each role
[24](#identification-and-authentication-for-each-role)](#identification-and-authentication-for-each-role)

[5.2.4 Roles requiring separation of duties
[25](#roles-requiring-separation-of-duties)](#roles-requiring-separation-of-duties)

[5.3 Personnel Security Controls
[25](#personnel-security-controls)](#personnel-security-controls)

[5.3.1 Qualifications, experience, and clearance requirements
[25](#qualifications-experience-and-clearance-requirements)](#qualifications-experience-and-clearance-requirements)

[5.3.2 Background check procedures
[25](#background-check-procedures)](#background-check-procedures)

[5.3.3 Training requirements
[25](#training-requirements)](#training-requirements)

[5.3.4 Retraining frequency and requirements
[25](#retraining-frequency-and-requirements)](#retraining-frequency-and-requirements)

[5.3.5 Job rotation frequency and sequence
[25](#job-rotation-frequency-and-sequence)](#job-rotation-frequency-and-sequence)

[5.3.6 Sanctions for unauthorized actions
[25](#sanctions-for-unauthorized-actions)](#sanctions-for-unauthorized-actions)

[5.3.7 Independent contractor requirements
[25](#independent-contractor-requirements)](#independent-contractor-requirements)

[5.3.8 Documentation supplied to personnel
[25](#documentation-supplied-to-personnel)](#documentation-supplied-to-personnel)

[5.3.9 Contract termination and assigned role change procedures
[25](#contract-termination-and-assigned-role-change-procedures)](#contract-termination-and-assigned-role-change-procedures)

[5.4 Audit Logging Procedures
[25](#audit-logging-procedures)](#audit-logging-procedures)

[5.4.1 Types of events recorded
[25](#types-of-events-recorded)](#types-of-events-recorded)

[5.4.2 Frequency of processing log
[25](#frequency-of-processing-log)](#frequency-of-processing-log)

[5.4.3 Retention period for audit log
[26](#retention-period-for-audit-log)](#retention-period-for-audit-log)

[5.4.4 Protection of audit log
[26](#protection-of-audit-log)](#protection-of-audit-log)

[5.4.5 Audit log backup procedures
[26](#audit-log-backup-procedures)](#audit-log-backup-procedures)

[5.4.6 Audit collection system (internal vs. external)
[26](#audit-collection-system-internal-vs.-external)](#audit-collection-system-internal-vs.-external)

[5.4.7 Notification to event-causing subject
[26](#notification-to-event-causing-subject)](#notification-to-event-causing-subject)

[5.4.8 Vulnerability assessments
[26](#vulnerability-assessments)](#vulnerability-assessments)

[5.5 Records Archival [26](#records-archival)](#records-archival)

[5.5.1 Types of records archived
[26](#types-of-records-archived)](#types-of-records-archived)

[5.5.2 Retention period for archive
[26](#retention-period-for-archive)](#retention-period-for-archive)

[5.5.3 Protection of archive
[26](#protection-of-archive)](#protection-of-archive)

[5.5.4 Archive backup procedures
[26](#archive-backup-procedures)](#archive-backup-procedures)

[5.5.5 Requirements for time-stamping of records
[26](#requirements-for-time-stamping-of-records)](#requirements-for-time-stamping-of-records)

[5.5.6 Archive collection system (internal or external)
[26](#archive-collection-system-internal-or-external)](#archive-collection-system-internal-or-external)

[5.5.7 Procedures to obtain and verify archive information
[26](#procedures-to-obtain-and-verify-archive-information)](#procedures-to-obtain-and-verify-archive-information)

[5.6 Key Changeover [27](#key-changeover)](#key-changeover)

[5.7 Compromise and Disaster Recovery
[27](#compromise-and-disaster-recovery)](#compromise-and-disaster-recovery)

[5.7.1 Incident and compromise handling procedures
[27](#incident-and-compromise-handling-procedures)](#incident-and-compromise-handling-procedures)

[5.7.2 Computing resources, software, and/or data are corrupted
[27](#computing-resources-software-andor-data-are-corrupted)](#computing-resources-software-andor-data-are-corrupted)

[5.7.3 Entity private key compromise procedures
[27](#entity-private-key-compromise-procedures)](#entity-private-key-compromise-procedures)

[5.7.4 Business continuity capabilities after a disaster
[27](#business-continuity-capabilities-after-a-disaster)](#business-continuity-capabilities-after-a-disaster)

[5.8 CA or RA Termination
[27](#ca-or-ra-termination)](#ca-or-ra-termination)

[6 Technical Security Controls
[28](#technical-security-controls)](#technical-security-controls)

[6.1 Key Pair Generation and Installation
[28](#key-pair-generation-and-installation)](#key-pair-generation-and-installation)

[6.1.1 Key pair generation
[28](#key-pair-generation)](#key-pair-generation)

[6.1.2 Private key delivery to subscriber
[28](#private-key-delivery-to-subscriber)](#private-key-delivery-to-subscriber)

[6.1.3 Public key delivery to certificate issuer
[28](#public-key-delivery-to-certificate-issuer)](#public-key-delivery-to-certificate-issuer)

[6.1.4 CA public key delivery to relying parties
[28](#ca-public-key-delivery-to-relying-parties)](#ca-public-key-delivery-to-relying-parties)

[6.1.5 Key sizes [28](#key-sizes)](#key-sizes)

[6.1.6 Public key parameters generation and quality checking
[28](#public-key-parameters-generation-and-quality-checking)](#public-key-parameters-generation-and-quality-checking)

[6.1.7 Key usage purposes (as per X.509 v3 key usage field)
[28](#key-usage-purposes-as-per-x.509-v3-key-usage-field)](#key-usage-purposes-as-per-x.509-v3-key-usage-field)

[6.2 Private Key Protection and Cryptographic Module Engineering
Controls
[28](#private-key-protection-and-cryptographic-module-engineering-controls)](#private-key-protection-and-cryptographic-module-engineering-controls)

[6.2.1 Cryptographic module standards and controls
[29](#cryptographic-module-standards-and-controls)](#cryptographic-module-standards-and-controls)

[6.2.2 Private key (n out of m) multi-person control
[29](#private-key-n-out-of-m-multi-person-control)](#private-key-n-out-of-m-multi-person-control)

[6.2.3 Private key escrow
[29](#private-key-escrow)](#private-key-escrow)

[6.2.4 Private key backup
[29](#private-key-backup)](#private-key-backup)

[6.2.5 Private key archival
[29](#private-key-archival)](#private-key-archival)

[6.2.6 Private key transfer into or from a cryptographic module
[29](#private-key-transfer-into-or-from-a-cryptographic-module)](#private-key-transfer-into-or-from-a-cryptographic-module)

[6.2.7 Private key storage on cryptographic module
[29](#private-key-storage-on-cryptographic-module)](#private-key-storage-on-cryptographic-module)

[6.2.8 Method of activating private key
[29](#method-of-activating-private-key)](#method-of-activating-private-key)

[6.2.9 Method of deactivating private key
[29](#method-of-deactivating-private-key)](#method-of-deactivating-private-key)

[6.2.10 Method of destroying private key
[29](#method-of-destroying-private-key)](#method-of-destroying-private-key)

[6.2.11 Cryptographic Module Rating
[29](#cryptographic-module-rating)](#cryptographic-module-rating)

[6.3 Other Aspects of Key Pair Management
[29](#other-aspects-of-key-pair-management)](#other-aspects-of-key-pair-management)

[6.3.1 Public key archival
[29](#public-key-archival)](#public-key-archival)

[6.3.2 Certificate operational periods and key pair usage periods
[29](#certificate-operational-periods-and-key-pair-usage-periods)](#certificate-operational-periods-and-key-pair-usage-periods)

[6.4 Activation Data [30](#activation-data)](#activation-data)

[6.4.1 Activation data generation and installation
[30](#activation-data-generation-and-installation)](#activation-data-generation-and-installation)

[6.4.2 Activation data protection
[30](#activation-data-protection)](#activation-data-protection)

[6.4.3 Other aspects of activation data
[30](#other-aspects-of-activation-data)](#other-aspects-of-activation-data)

[6.5 Computer Security Controls
[30](#computer-security-controls)](#computer-security-controls)

[6.5.1 Specific computer security technical requirements
[30](#specific-computer-security-technical-requirements)](#specific-computer-security-technical-requirements)

[6.5.2 Computer security rating
[30](#computer-security-rating)](#computer-security-rating)

[6.6 Life Cycle Security Controls
[30](#life-cycle-security-controls)](#life-cycle-security-controls)

[6.6.1 System development controls
[30](#system-development-controls)](#system-development-controls)

[6.6.2 Security management controls
[30](#security-management-controls)](#security-management-controls)

[6.6.3 Life cycle security controls
[30](#life-cycle-security-controls-1)](#life-cycle-security-controls-1)

[6.7 Network Security Controls
[30](#network-security-controls)](#network-security-controls)

[6.8 Time-stamping [30](#time-stamping)](#time-stamping)

[7 Certificate and CRL Profiles
[31](#certificate-and-crl-profiles)](#certificate-and-crl-profiles)

[7.1 Certificate Profile
[31](#certificate-profile)](#certificate-profile)

[7.1.1 Version number(s) [31](#version-numbers)](#version-numbers)

[7.1.2 Certificate extensions
[31](#certificate-extensions)](#certificate-extensions)

[7.1.3 Algorithm object identifiers
[33](#algorithm-object-identifiers)](#algorithm-object-identifiers)

[7.1.4 Name forms [33](#name-forms)](#name-forms)

[7.1.5 Name constraints [33](#name-constraints)](#name-constraints)

[7.1.6 Certificate policy object identifier
[33](#certificate-policy-object-identifier)](#certificate-policy-object-identifier)

[7.1.7 Usage of Policy Constraints extension
[34](#usage-of-policy-constraints-extension)](#usage-of-policy-constraints-extension)

[7.1.8 Policy qualifiers syntax and semantics
[34](#policy-qualifiers-syntax-and-semantics)](#policy-qualifiers-syntax-and-semantics)

[7.1.9 Processing semantics for the critical Certificate Policies
extension
[34](#processing-semantics-for-the-critical-certificate-policies-extension)](#processing-semantics-for-the-critical-certificate-policies-extension)

[7.2 CRL Profile [34](#crl-profile)](#crl-profile)

[7.2.1 Version number(s) [34](#version-numbers-1)](#version-numbers-1)

[7.2.2 CRL Profile and CRL entry extensions
[34](#crl-profile-and-crl-entry-extensions)](#crl-profile-and-crl-entry-extensions)

[7.3 OCSP Profile [34](#ocsp-profile)](#ocsp-profile)

[7.3.1 Version number(s) [34](#version-numbers-2)](#version-numbers-2)

[7.3.2 OCSP extensions [34](#ocsp-extensions)](#ocsp-extensions)

[8 Compliance Audit and Other Assessment
[35](#compliance-audit-and-other-assessment)](#compliance-audit-and-other-assessment)

[8.1 Frequency or circumstances of assessment
[35](#frequency-or-circumstances-of-assessment)](#frequency-or-circumstances-of-assessment)

[8.2 Identity/qualifications of assessor
[35](#identityqualifications-of-assessor)](#identityqualifications-of-assessor)

[8.3 Assessor's relationship to assessed entity
[35](#assessors-relationship-to-assessed-entity)](#assessors-relationship-to-assessed-entity)

[8.4 Topics covered by assessment
[35](#topics-covered-by-assessment)](#topics-covered-by-assessment)

[8.5 Actions taken as a result of deficiency
[35](#actions-taken-as-a-result-of-deficiency)](#actions-taken-as-a-result-of-deficiency)

[8.6 Communication of results
[35](#communication-of-results)](#communication-of-results)

[9 Other Business and Legal Matters
[36](#other-business-and-legal-matters)](#other-business-and-legal-matters)

[9.1 Fees [36](#fees)](#fees)

[9.1.1 Certificate issuance or renewal fees
[36](#certificate-issuance-or-renewal-fees)](#certificate-issuance-or-renewal-fees)

[9.1.2 Certificate access fees
[36](#certificate-access-fees)](#certificate-access-fees)

[9.1.3 Revocation or status information access fees
[36](#revocation-or-status-information-access-fees)](#revocation-or-status-information-access-fees)

[9.1.4 Fees for other services
[36](#fees-for-other-services)](#fees-for-other-services)

[9.1.5 Refund policy [36](#refund-policy)](#refund-policy)

[9.2 Financial Responsibility
[36](#financial-responsibility)](#financial-responsibility)

[9.2.1 Insurance coverage
[36](#insurance-coverage)](#insurance-coverage)

[9.2.2 Other assets [36](#other-assets)](#other-assets)

[9.2.3 Insurance or warranty coverage for end-entities
[36](#insurance-or-warranty-coverage-for-end-entities)](#insurance-or-warranty-coverage-for-end-entities)

[9.3 Confidentiality of Business Information
[36](#confidentiality-of-business-information)](#confidentiality-of-business-information)

[9.3.1 Scope of confidential information
[36](#scope-of-confidential-information)](#scope-of-confidential-information)

[9.3.2 Information not within the scope of confidential information
[36](#information-not-within-the-scope-of-confidential-information)](#information-not-within-the-scope-of-confidential-information)

[9.3.3 Responsibility to protect confidential information
[37](#responsibility-to-protect-confidential-information)](#responsibility-to-protect-confidential-information)

[9.4 Privacy of Personal Information
[37](#privacy-of-personal-information)](#privacy-of-personal-information)

[9.4.1 Privacy plan [37](#privacy-plan)](#privacy-plan)

[9.4.2 Information treated as private
[37](#information-treated-as-private)](#information-treated-as-private)

[9.4.3 Information not deemed private
[37](#information-not-deemed-private)](#information-not-deemed-private)

[9.4.4 Responsibility to protect private information
[37](#responsibility-to-protect-private-information)](#responsibility-to-protect-private-information)

[9.4.5 Notice and consent to use private information
[37](#notice-and-consent-to-use-private-information)](#notice-and-consent-to-use-private-information)

[9.4.6 Disclosure pursuant to judicial or administrative process
[37](#disclosure-pursuant-to-judicial-or-administrative-process)](#disclosure-pursuant-to-judicial-or-administrative-process)

[9.4.7 Other information disclosure circumstances
[37](#other-information-disclosure-circumstances)](#other-information-disclosure-circumstances)

[9.5 Intellectual Property Rights
[37](#intellectual-property-rights)](#intellectual-property-rights)

[9.6 Representations and Warranties
[37](#representations-and-warranties)](#representations-and-warranties)

[9.6.1 CA representations and warranties
[37](#ca-representations-and-warranties)](#ca-representations-and-warranties)

[9.6.2 RA representations and warranties
[37](#ra-representations-and-warranties)](#ra-representations-and-warranties)

[9.6.3 Subscriber representations and warranties
[37](#subscriber-representations-and-warranties)](#subscriber-representations-and-warranties)

[9.6.4 Relying party representations and warranties
[38](#relying-party-representations-and-warranties)](#relying-party-representations-and-warranties)

[9.6.5 Representations and warranties of other participants
[38](#representations-and-warranties-of-other-participants)](#representations-and-warranties-of-other-participants)

[9.7 Disclaimers of Warranties
[38](#disclaimers-of-warranties)](#disclaimers-of-warranties)

[9.8 Limitations of Liability
[38](#limitations-of-liability)](#limitations-of-liability)

[9.9 Indemnities [38](#indemnities)](#indemnities)

[9.10 Term and Termination
[38](#term-and-termination)](#term-and-termination)

[9.10.1 Term [38](#term)](#term)

[9.10.2 Termination [38](#termination)](#termination)

[9.10.3 Effect of termination and survival
[38](#effect-of-termination-and-survival)](#effect-of-termination-and-survival)

[9.11 Individual notices and communications with participants
[38](#individual-notices-and-communications-with-participants)](#individual-notices-and-communications-with-participants)

[9.12 Amendments [38](#amendments)](#amendments)

[9.12.1 Procedure for amendment
[38](#procedure-for-amendment)](#procedure-for-amendment)

[9.12.2 Notification mechanism and period
[38](#notification-mechanism-and-period)](#notification-mechanism-and-period)

[9.12.3 Circumstances under which OID must be changed
[38](#circumstances-under-which-oid-must-be-changed)](#circumstances-under-which-oid-must-be-changed)

[9.13 Dispute Resolution Procedures
[39](#dispute-resolution-procedures)](#dispute-resolution-procedures)

[9.14 Governing Law [39](#governing-law)](#governing-law)

[9.15 Compliance with Applicable Law
[39](#compliance-with-applicable-law)](#compliance-with-applicable-law)

[9.16 Miscellaneous Provisions
[39](#miscellaneous-provisions)](#miscellaneous-provisions)

[9.16.1 Entire agreement [39](#entire-agreement)](#entire-agreement)

[9.16.2 Assignment [39](#assignment)](#assignment)

[9.16.3 Severability [39](#severability)](#severability)

[9.16.4 Enforcement (attorneys' fees and waiver of rights)
[39](#enforcement-attorneys-fees-and-waiver-of-rights)](#enforcement-attorneys-fees-and-waiver-of-rights)

[9.16.5 Force Majeure [39](#force-majeure)](#force-majeure)

[9.17 Other Provisions [39](#other-provisions)](#other-provisions)

[10 Annex A: Glossary [40](#annex-a-glossary)](#annex-a-glossary)

# Introductions

## Overview

The Certification Policy (CP) documents published by the OISTE
Foundation describe the stipulations to be implemented by any
Certification Authority, adhered to the OISTE Global Trust Model, in
order to issue and manage certificates of a particular type.

**This CP document discloses the stipulations related to “SSL
Certificates”, intended to be issued to, and used by, Software
Applications, such web servers, requiring a “Server Authentication”
capability. The stipulations of this CP have been defined in compliance
of the “Baseline Requirements for SSL Certificates” issued by the
CA/Browser Forum, to which all CAs operating under the OISTE Global
Trust Model with capability to issue SSL Certificates must commit**

**About the OISTE Foundation**: The International Organization for
Secure Electronic Transactions (“IOSET” or “OISTE”), a Swiss non-profit
foundation established in 1998, and recognized with an “Special
Consultative Status” by the United Nations. The OISTE Foundation
maintains a Policy Approval Authority (OFPAA or PAA) that drafts,
approves and revises the policies to which WISeKey is bound to comply
with under its operator contract. The PAA is composed of members of the
community to which OISTE provides its Certification Authority Services,
resulting in a virtuous cycle for trust management.

The OISTE Global Trust Model (**OGTM from now on**) has been designed
and are operated in accordance with the broad strategic direction of
international PKI (Public Key Infrastructure) standards as well as their
application to concrete identity frameworks in different domains (e.g.
ID cards, passports, health cards, Internet of Things) and is intended
to serve as a common Trust Model for Certification Authorities worldwide
that comply with OISTE requirements.

The OISTE Foundation, under Swiss law, cannot belong to any individual
or company. It is subject to annual supervision by the Swiss Federal
Government and audited annually by independent auditors. Such
supervision and audit require the foundation to pursue the objectives
that have been set out for it, which includes the promotion of security
in electronic communications worldwide.

This document is developed per the recommendations found in the document
**RFC3647** issued by *The Internet Society* in 2003, which has been
adopted as a worldwide-recognized standard framework to document the
Certifications Practice Statement and related Certificate Policies
disclosed by a Certification Services Provider.

The purpose of the CP documents is to disclose the Policies to be
adopted in the **OGTM** for the issuance of digital certificates. It is
organized in the following sections:

1.  Introductions – This section. Introduces the **OGTM** and this
    document.

2.  Publication and Repositories Responsibilities – Describes the
    publication policies for the certificates affected by this document,
    and the publication of this document itself.

3.  Identification and Authentication – Discloses the rules for
    subscriber naming and required authentication policies.

4.  Certificate Life-Cycle Operational Requirements – This section
    describes the different phases in the Life-Cycle of certificates and
    their requirements.

5.  Management, Operational and Physical Controls – Describes the
    controls enforced in the **OGTM** to provide adequate trust levels
    in the certificates issued under the Trust Model.

6.  Technical Security Controls – Discloses the security controls
    adopted in the **OGTM**.

7.  Certificate and CRL Profiles – Describes the technical details of
    the different certificate types issued under the **OGTM**.

8.  Compliance Audit and other Assessment – Discloses the audit policies
    followed in the **OGTM** to ensure that the participant fulfils the
    security and quality requirements.

9.  Other Business and Legal Matters – This section exposes the
    commercial, legal and contractual aspects involved in the usage of
    certificates issued in the **OGTM**.

### The OGTM CP/CPS Documentation Framework

The main information disclosed by the **OGTM** in order to expose its
practices and policies in the issuance and usages of digital
certificates are:

-   The Certification Practices Statement (CPS) –The CPS is a statement
    of the practices that every Certification Authority operating under
    the **OGTM** Trust Model employs in issuing, managing, revoking, and
    renewing or re-keying certificates. This CPS document discloses the
    stipulations related to the issuance of Subordinate CA Certificates,
    assigned to entities acting as “Issuing Certification Authorities”
    under the **OGTM**. Those entities must publish their own CPS to
    disclose the stipulations related to end-entity certification
    practices. ***Any explicit mention to a CP document must be
    understood as referring to the appropriate CP document for the
    certificate type being evaluated***.

-   A number of Certificate Policies (CP) – each being a named set of
    rules that indicates the applicability of a type or profile of
    certificate to a particular community and/or class of application
    with common security requirements.

**The CP/CPS hierarchy and documentation framework is regulated by the
OISTE Foundation and disclosed in http://www.oiste.org/repository.**

The CPS and CP documents follow the same structure, the second being a
specialization of the CPS for a certain type of certificate. Common
policies and practices are only published within the CPS. For the
convenience of readers of this CP, the sections that are generally
specified within the CPS are clearly noted with the sentence: *“As
stipulated in the CPS published by the Issuing CA”*.

## Document Name and Identification

<table>
<colgroup>
<col style="width: 16%" />
<col style="width: 83%" />
</colgroup>
<tbody>
<tr>
<td><strong>Name</strong></td>
<td>OGTM Certificate Policy for SSL Certificates</td>
</tr>
<tr>
<td><strong>Version</strong></td>
<td>1.6</td>
</tr>
<tr>
<td><strong>OID</strong></td>
<td>2.16.756.5.14.7.1</td>
</tr>
<tr>
<td><strong>Issuance date</strong></td>
<td>18/7/2024</td>
</tr>
<tr>
<td><strong>Location</strong></td>
<td>This document can be found at /repository</td>
</tr>
</tbody>
</table>

## PKI Participants

### Certification authorities

The current full list of Certification Authorities that have been
authorized by OISTE to operate under the **OGTM** and implement this
particular CP is disclosed in **http://www.oiste.org/repository**.

### Registration authorities

*As stipulated in the CPS published by the Issuing CA.*

### Subscribers

In the **OWGTM** two different end-user roles are defined. Depending on
the status of the certificate request, these roles are named “Applicant”
and “Subscriber”.

An *applicant* is a physical person that requests a certificate for his
own behalf or on behalf of a third party. The applicant needs to
accredit his identity and ability to request a certificate. In the case
of an applicant acting on behalf of a third party or legal person, he
will be requested to accredit the empowerment for such representation,
as required by law.

A *subscriber* is the physical or legal person whose identity is linked
to the electronic signature creation data, or private key, and included
in a digital certificate. In general, a subscriber is considered the
“owner” of a certificate. The subscriber of a certificate is responsible
for the custody of his private key and not communicating this data in
any way to any other person.

Subscribers for certificates issued under this CP are, in perticular,
natural and legal persons requiring to protect their internet and
communication servers, by means of authentication and encryption.

### Relying parties

All persons and entities that trust the certificates issued by
certification authorities operating under the **OGTM** Trust Model are
considered to be “relying parties” (or trusted third parties). These
relying parties do not necessarily need to be a subscriber of an
**OGTM** certificate but are requested to accept the “Relying Party
agreement “, as disclosed by the Issuing CA in its CPS.

### Other participants

*As stipulated in the CPS published by the Issuing CA.*

## Certificate Usage

### Appropriate Certificate Uses

<table>
<colgroup>
<col style="width: 29%" />
<col style="width: 36%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">CP Identifier</th>
<th style="text-align: left;">Description</th>
<th style="text-align: left;">Permitted uses</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">OISTE Standard DV SSL<a href="#fn1"
class="footnote-ref" id="fnref1" role="doc-noteref"><sup>1</sup></a>
Certificate</td>
<td style="text-align: left;"><p>Medium assurance SSL/TLS
certificate.</p>
<p>All identification attributes in the certificate are verified. The
control on the Internet Domain is validated. Compliant with CA/Browser
Forum Baseline Requirements.</p></td>
<td style="text-align: left;">Digital Signature, Encryption, Server
Authentication</td>
</tr>
<tr>
<td style="text-align: left;">OISTE Advanced OV SSL Certificate</td>
<td style="text-align: left;"><p>High assurance SSL/TLS certificate.</p>
<p>All identification attributes in the certificate are verified. The
Identity of the organization is validated. Compliant with CA/Browser
Forum Baseline Requirements.</p></td>
<td style="text-align: left;">Digital Signature, Encryption, Server
Authentication</td>
</tr>
<tr>
<td style="text-align: left;">OISTE Advanced EV SSL Certificate</td>
<td style="text-align: left;"><p>High assurance SSL/TLS certificate.</p>
<p>All identification attributes in the certificate are verified. The
Identity of the organization is validated. Compliant with CA/Browser
Requirements for Extended Validation.</p></td>
<td style="text-align: left;">Digital Signature, Encryption, Server
Authentication</td>
</tr>
</tbody>
</table>
<section id="footnotes" class="footnotes footnotes-end-of-document"
role="doc-endnotes">
<hr />
<ol>
<li id="fn1"><p>Note: SSL Certificates can be offered in different
versions (e.g. Wildcard or Unified Communications), but always according
to the applicable base CP and CA/Browser Forum requirements.<a
href="#fnref1" class="footnote-back" role="doc-backlink">REF</a></p></li>
</ol>
</section>

### Prohibited certificate uses

In general, any usage that is not explicitly stated in section 1.4.1 of
this document, is considered to be prohibited.

## Policy Administration

### Organization administering the document

This document is administered by the **OGTM Policy Approval Authority**
(referred from now as **PAA**).

The **PAA** has a series of distinct functions but does not operate as a
separate legal Entity. It is managed and organized in accordance with a
process that draws on expertise within the OISTE Foundation. The **PAA**
has been established to develop, review and/or approve the practices,
policies and procedures for the entire Trust Model, subject to
guidelines established by the members and advisors of the OISTE
Foundation.

### Contact Person (Contact Information)

<table>
<colgroup>
<col style="width: 24%" />
<col style="width: 75%" />
</colgroup>
<tbody>
<tr>
<td><strong>Name</strong></td>
<td>OISTE Foundation - OGTM Policy Approval Authority</td>
</tr>
<tr>
<td><strong>email address</strong></td>
<td>cps@oiste.org</td>
</tr>
<tr>
<td><strong>Address</strong></td>
<td style="text-align: left;">Av. Louis-Casaï, 58<br />
CH-1216 Cointrin - Geneva (Switzerland)</td>
</tr>
</tbody>
</table>

### Person determining CPS suitability for the policy

The competent entity which determines the compliance and suitability of
all CPS and the different supported CPs on behalf of the entire Trust
Model is the **OGTM PAA**.

### CPS approval procedures

The **OGTM PAA** defines and executes the procedures related to the
approval of the CPS and CP and its subsequent amendments. Amendments
will produce a new version of the document that will be published in the
**OGTM** Policy Repository (specified in section 2.1 of this document).

The approval of major changes of documents related to the PKI, and
specially for the CPS and CP, require a meeting of the PAA and the
issuance of an approval memo signed by at least two members of the PAA.
Minor versions only require the participation of a single member of the
PAA in order to approve the publication of a new version.

It’s required to issue new CP/CPS versions at least once a year. In the
case of versioning conflict, the latest version that prevails is always
the document published in the Policy Repository.

## Definitions and Acronyms

Definitions and Acronyms are included in Annex A (Glossary).

# Publication and Repository Responsibilities

This section contains the provisions regarding the publication of
policies, certificates and other public information needed for the
participants to interoperate with the **OGTM**, in what respects in
particular to the certificates issued to Persons. The general
stipulations will be published in the appropriate CPS.

## Repositories

The main repositories of the **OGTM** are:

-   Policies repository for disclosure of CP, CPS and related
    information. This repository is a set of web pages and services
    available at the URL /repository

-   Certificate and Certificate Revocation information repositories: *As
    stipulated in the CPS published by the Issuing CA.*

## Publication

*As stipulated in the CPS published by the Issuing CA.*

## Time or frequency of publication

The CPS and CP documents will be published every time they are modified,
with a minimum review period of one year.

A certificate issued by any CA under the **OGTM** will be published
immediately after its issuance.

In the case of revocation of a certificate, the appropriate CA will
include this revocation information in the Certificate Revocation Lists
(CRL) according to section 4.9.7 (CRL issuance frequency).

## Access control on repositories

*As stipulated in the CPS published by the Issuing CA.*

# Identification and Authentication

The **OGTM** mandates the fulfilment of a set of required minimum
controls that ensure the authenticity of the data included in
certificates. These controls are enforced during the full lifecycle of
certificates, certificate requests, and related documents. If
non-validated attributes are allowed for a certain type of certificate,
it will be explicitly indicated in the appropriate CP document and/or in
the certificate itself.

**This document reflects the common practices to be implemented by an
Issuing CA authorized to issue SSL Certificates.**

**If this CP allows multiple practices for a particular section, it must
be understood that this CP will stipulate all the allowed practices and
that the CPS disclosed by the Subordinate CA can particularize which
practices are implemented and the relevant details on the process.**

## Naming

This section describes the elements regarding naming and identifying the
subscribers of **OGTM** certificates.

### Types of names

All subscribers are assigned a Distinguished Name (DN) according to the
X.501 Standard. This DN is optionally composed of a Common Name (CN),
which includes a unique identification of the subscriber as described in
section 3.1.4.2, and a structure of X.501 components as defined in
section 3.1.4.

### Need for names to be meaningful

All Distinguished Names must be meaningful, and the identification the
attributes associated to the subscriber should be in a human readable
form.

### Anonymity of subscribers and pseudonyms

This CP doesn’t allow anonymity or pseudonyms in the SSL certificates.

### Rules for interpreting various name forms

The rules used in the **OGTM** to interpret the distinguished names of
certificates issued under its Trust Model are defined by the ISO/IEC
9595 (X.500) Distinguished Name (DN) standard.

### Uniqueness of names

The uniqueness of names for SSL Certificates must be assured by
*requiring a combination of domain names, organization name
combined/associated with a unique serial integer.*

### Recognition, authentication, and role of trademarks

*As stipulated in the CPS published by the Issuing CA.*

## Initial Identity Validation

Issuing CAs implementing this CP must perform the identity validation as
stipulated in the following sections.

### Method to prove possession of private key

If the key pair is generated by the End Entity (applicant or future
subscriber), then a demonstration of the possession of the private key
associated to the public key is requested. Accepted means are the
generation of a Certificate Signing Request (CSR) linked to the private
key, or equivalent methods implemented by the Issuing CA.

### Authentication of organization identity

The authentication of organization identity for SSL certificates will
follow the following rules. **The Issuing CA must detail in its CPS
which of the methods are used and how are implemented.**

<table>
<colgroup>
<col style="width: 30%" />
<col style="width: 69%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">CP Identifier</th>
<th>Validation Policy</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">OISTE Standard DV SSL Certificate</td>
<td>The Issuing CA must validate the Applicant’s right to use or control
each domain name that will be listed in the Subject Alternative Name
field of a Certificate by using at least one of the procedures listed in
section 3.2.2.4 o the Baseline Requirements.</td>
</tr>
<tr>
<td style="text-align: left;">OISTE Advanced OV SSL Certificate</td>
<td><p>The Issuing CA must execute the domain validation procedures as
required for DV SSL certificates.</p>
<p>Additionally, the Issuing CA must verify:</p>
<ul>
<li><p>The identity and address of the Applicant using the procedures
found in section 3.2.2.1 and/or section 3.2.3 of the Baseline
Requirements.</p></li>
<li><p>Any DBA included in a Certificate using a third party or
government source, attestation letter, or reliable form of
identification in accordance with section 3.2.2 of the Baseline
Requirements.</p></li>
</ul></td>
</tr>
<tr>
<td style="text-align: left;">OISTE Advanced EV SSL Certificate</td>
<td><p>The Issuing CA must execute the domain validation procedures as
required for DV and OV SSL certificates.</p>
<p>Additionally, the Issuing CA must do the specific validations
mandated by the EV Guidelines issued by the CAB/Forum.</p></td>
</tr>
</tbody>
</table>

**Additionally, the Issuing CA must reference in its CPS the list of
validation sources using for these verifications.**

### Authentication of individual identity

The RA designated by the Issuing CA should obtain from the Applicant a
valid Photo-ID issued by a competent government. Further identity proofs
can be required if necessary.

*In particular for EV SSL certificates, the Issuing CA must endure
compliance with the EV Guidelines.*

### Non-verified subscriber information

**OGTM** doesn’t allow to include non-verified identity-related
information in any certificate issued by a certification authority
operating in the trust model.

### Validation of authority

The validation of authority for SSL certificates will follow the
following rules. **The Issuing CA must detail in its CPS which of the
methods are used and how are implemented.**

<table>
<colgroup>
<col style="width: 30%" />
<col style="width: 69%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">CP Identifier</th>
<th>Validation Policy</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align: left;">OISTE Standard DV SSL Certificate</td>
<td>The Issuing CA must verify the authority of the requester is
verified by using one or more of the procedures listed in section
3.2.2.4. of the Baseline Requirements.</td>
</tr>
<tr>
<td style="text-align: left;">OISTE Advanced OV SSL Certificate</td>
<td>The Issuing CA must verify the authority of the requester is
verified by using one or more of the procedures listed in section 3.2.5.
of the Baseline Requirements.</td>
</tr>
<tr>
<td style="text-align: left;">OISTE Advanced EV SSL Certificate</td>
<td>The Issuing CA must apply the requirements of section 11.8.3 of the
EV Guidelines.</td>
</tr>
</tbody>
</table>

### Criteria for interoperation

*As stipulated in the CPS published by the Issuing CA.*

## Identification and Authentication for Re-key Requests

This section addresses the following elements for the identification and
authentication procedures for re-key for each subject type (CA, RA,
subscriber, and other participants). Unless otherwise specified, it can
considered as equivalent the activities linked to “re-key” (new
certificate for an existing subscriber, using a new key pair) and
“renewal” (new certificate for an existing subscriber, using the same
key pair).

### Identification and authentication for routine re-key

The certificate subscriber can request a routine re-key by
authenticating himself with one of these methods:

-   Username & Password

-   A valid digital certificate linked to the user account

The information of the subscriber must be revalidated periodically, in
particular for SSL Certificates the maximum reuse period is as defined
by the CAB/Forum (397 days).

### Identification and authentication for re-key after revocation

The **OGTM** does not support re-key of certificates after revocation.
The subscriber must apply for a new digital certificate by using the
same procedures as for its issuance.

## Identification and Authentication for Revocation Requests

The Identification Policy for revocation requests is the same as
stipulated for routine re-keys.

# Certificate Life-Cycle Operational Requirements

The stipulations included in this section are generally disclosed in the
CPS published by the Issuing CA, unless otherwise specified in the
following sub-sections.

## Certificate Application

*As stipulated in the CPS published by the Issuing CA.*

### Who can submit a certificate application

A certificate application can be submitted by the subject of the
certificate or by an authorized representative of the subject.

### Enrolment process and responsibilities

The Issuer CA is responsible for ensuring that the identity of each
Certificate Applicant is verified in accordance with this CP and the
applicable CPS prior to the issuance of a Certificate. Applicants are
responsible for submitting sufficient information and documentation to
the RA to perform the required verification of identity prior to issuing
a Certificate.

## Certificate Application Processing

This section describes the procedures for processing certificate
applications in the **OGTM** Trust Model.

### Performing identification and authentication functions

The identification and authentication functions can be delegated by the
Issuing CA to the Registration Authorities operating under the **OGTM**.

The steps to be executed by the Issuing CA or RA are as follows:

-   As a first step, the Issuing CA or RA will perform the verifications
    stipulated in section 3.2.

-   As a second step, the CA must check the DNS for the existence of a
    CAA record for each dNSName in the subjectAltName extension of the
    certificate to be issued, according to the procedure in RFC 6844.
    **The Issuing CA must specify in its CPS the domains that must
    appear in the CAA records.**

-   As a third step, the Issuing CA must check the certificate details
    against a list of previously revoked Certificates and rejected
    certificate requests to identify suspicious certificate requests.

The Issuing CA can only issue a certificate after having successfully
completed the above steps.

### Approval or rejection of certificate applications

An approval of a certificate application derives from the execution of
the certificate issuance procedures, as defined in the section 4.3 of
this Certificate Policy and the appropriate CPS.

A rejection of a certificate application results in a notification being
sent to the applicant by appropriate means and is registered for further
reference.

### Time to process certificate applications

There is no time limit stipulated to complete the processing of an
application.

## Certificate Issuance

An approved certificate request will be processed by the authorized
responsible.

### CA actions during certificate issuance

*As stipulated in the CPS published by the Issuing CA.*

### Notifications to subscriber by the CA of issuance of certificate

*As stipulated in the CPS published by the Issuing CA.*

## Certificate Acceptance

*As stipulated in the CPS published by the Issuing CA.*

### Conduct constituting certificate acceptance

*As stipulated in the CPS published by the Issuing CA.*

### Publication of the certificate by the CA

The CAs operating under the **OGTM** publish all issued certificates as
specified in section 2 of this document.

### Notification of certificate issuance by the CA to other entities

*As stipulated in the CPS published by the Issuing CA.*

## Key Pair and Certificate Usage

The certificates issued by the **OGTM** are used to provide
authenticity, integrity, confidentiality and/or non-repudiation in
electronic transactions and other computerized functions.

### Subscriber private key and certificate usage

Any party using these certificates shall use software that is compliant
with X.509 and applicable IETF PKIX standards. The Issuer CA can specify
restrictions on the use of a Certificate through certificate extensions
and shall specify the mechanism(s) to determine certificate validity
(CRLs and OCSP).

Relying Parties must process and comply with this information in
accordance with their obligations as per the Relaying Party Agreement
published by the Issuing CA.

### Relying party public key and certificate usage

*As stipulated in the CPS published by the Issuing CA.*

## Certificate Renewal

Certificate Renewal is understood as the issuance of a new certificate
to a subscriber who maintains the key pair generated for the original
certificate.

### Circumstance for certificate renewal

For SSL Certificates it is allowed the certificate renewal for the
purpose of extending the validity period and always considering the
requirements for re-verification periods stipulated in section 3.3 of
this CP.

### Who may request renewal

The certificate renewal can be requested by the same entities allowed to
request the first issuance of the certificate.

### Processing certificate renewal requests

Certificate renewal requests are processed according to the same rules
than the initial issuance*.*

### Notification of new certificate issuance to subscriber

*As stipulated in the CPS published by the Issuing CA.*

### Conduct constituting acceptance of a renewal certificate

*As stipulated in the CPS published by the Issuing CA.*

### Publication of the renewal certificate by the CA

The CAs operating under the **OGTM** publish all issued certificates as
specified in section 2 of this document.

### Notification of certificate issuance by the CA to other entities

*As stipulated in the CPS published by the Issuing CA.*

## Certificate Re-key

Certificate Re-Key is understood as the issuance of a new certificate to
a subscriber that also generates a new key pair. This process is
supported for all certificate types.

### Circumstance for certificate re-key

Any certificate that is not revoked can be re-keyed.

### Who may request certification of a new public key

The certificate renewal can be requested by the same entities allowed to
request the first issuance of the certificate.

### Processing certificate re-keying requests

Certificate re-key requests are processed according to the same rules
than the initial issuance*.*

### Notification of new certificate issuance to subscriber

*As stipulated in the CPS published by the Issuing CA.*

### Conduct constituting acceptance of a re-keyed certificate

*As stipulated in the CPS published by the Issuing CA.*

### Publication of the re-keyed certificate by the CA

The CAs operating under the **OGTM** publish all issued certificates as
specified in section 2 of this document.

### Notification of certificate issuance by the CA to other entities

*As stipulated in the CPS published by the Issuing CA.*

## Certificate Modification

The **OGTM** does not allow the modification of certificates during
their validity period. If the information contained in a certificate
ceases to be valid, or the circumstances of the subscriber change in
such a manner that the conditions expressed in the CPS or the CP are not
met, then the only accepted procedure is the revocation and reissuance
of a new certificate.

### Circumstance for certificate modification

Does not apply.

### Who may request certificate modification

Does not apply.

### Processing certificate modification requests

Does not apply.

### Notification of new certificate issuance to subscriber

Does not apply.

### Conduct constituting acceptance of modified certificate

Does not apply.

### Publication of the modified certificate by the CA

Does not apply.

### Notification of certificate issuance by the CA to other entities

Does not apply.

## Certificate Revocation and Suspension

All Certification Authorities operating under the **OGTM** ensure, by
establishing the necessary means, that a certificate that compromises
the Trust Model for any reason is prevented from being used by either
revoking or suspending that certificate.

Suspension of certificates is only supported for personal and device
certificates, and explicitly disallowed for SSL certificates, according
to the CA/Browser Forum requirements, and therefore is disallowed for
any certificate existing under an OISTE Root which is approved to issue
publicly trusted SSL certificates.

The stipulations for this section must be disclosed in the CPS, and
therefore the reader must refer to that document for more information.

### Circumstances for revocation

*As stipulated in the CPS published by the Issuing CA.*

### Who can request revocation

*As stipulated in the CPS published by the Issuing CA.*

### Procedure for revocation request

*As stipulated in the CPS published by the Issuing CA.*

### Revocation request grace period

*As stipulated in the CPS published by the Issuing CA.*

### Time within which CA must process the revocation request

*As stipulated in the CPS published by the Issuing CA.*

### Revocation checking requirement for relying parties

*As stipulated in the CPS published by the Issuing CA.*

### CRL issuance frequency

*As stipulated in the CPS published by the Issuing CA.*

### Maximum latency for CRLs

*As stipulated in the CPS published by the Issuing CA.*

### On-line revocation/status checking availability

*As stipulated in the CPS published by the Issuing CA.*

### On-line revocation checking requirements

*As stipulated in the CPS published by the Issuing CA.*

### Other forms of revocation advertisements available

No stipulations.

### Special requirements regarding key compromise

*As stipulated in the CPS published by the Issuing CA.*

### Circumstances for suspension

*Suspension is not permitted for SSL Certificates.*

### Who can request suspension

*Does not apply.*

### Procedure for suspension request

*Does not apply.*

### Limits on suspension period

*Does not apply.*

## Certificate Status Services

**For SSL Certificates, the Issuing CA must provide certificate status
validation services, by means of Certificate Revocation Lists and OCSP
responder. The details of such services must be detailed in the CPS
published by the Issuing CA.**

### Operational characteristics

*As stipulated in the CPS published by the Issuing CA.*

### Service availability

*As stipulated in the CPS published by the Issuing CA.*

### Optional features

No stipulation.

## End of Subscription

*As stipulated in the CPS published by the Issuing CA.*

## Key Escrow and Recovery

Key escrow is not permitted for SSL Certificates.

### Key escrow and recovery policy and practices

*Does not apply.*

### Session key encapsulation and recovery policy and practices

*Does not apply.*

# Management, Operational, and Physical Controls

*As stipulated in the CPS published by the Issuing CA.*

## Physical Security Controls

*As stipulated in the CPS published by the Issuing CA.*

### Site location and construction

*As stipulated in the CPS published by the Issuing CA.*

### Physical access

*As stipulated in the CPS published by the Issuing CA.*

### Power and air conditioning

*As stipulated in the CPS published by the Issuing CA.*

### Water exposures

*As stipulated in the CPS published by the Issuing CA.*

### Fire prevention and protection

*As stipulated in the CPS published by the Issuing CA.*

### Media storage

*As stipulated in the CPS published by the Issuing CA.*

### Waste disposal

*As stipulated in the CPS published by the Issuing CA.*

### Backup

*As stipulated in the CPS published by the Issuing CA.*

## Procedural Controls

*As stipulated in the CPS published by the Issuing CA.*

### Trusted roles

*As stipulated in the CPS published by the Issuing CA.*

### Number of persons required per task

*As stipulated in the CPS published by the Issuing CA.*

### Identification and authentication for each role

*As stipulated in the CPS published by the Issuing CA.*

### Roles requiring separation of duties

*As stipulated in the CPS published by the Issuing CA.*

## Personnel Security Controls

*As stipulated in the CPS published by the Issuing CA.*

### Qualifications, experience, and clearance requirements

*As stipulated in the CPS published by the Issuing CA.*

### Background check procedures

*As stipulated in the CPS published by the Issuing CA.*

### Training requirements

*As stipulated in the CPS published by the Issuing CA.*

### Retraining frequency and requirements

*As stipulated in the CPS published by the Issuing CA.*

### Job rotation frequency and sequence

*As stipulated in the CPS published by the Issuing CA.*

### Sanctions for unauthorized actions

*As stipulated in the CPS published by the Issuing CA.*

### Independent contractor requirements

*As stipulated in the CPS published by the Issuing CA.*

### Documentation supplied to personnel

*As stipulated in the CPS published by the Issuing CA.*

### Contract termination and assigned role change procedures

*As stipulated in the CPS published by the Issuing CA.*

## Audit Logging Procedures

*As stipulated in the CPS published by the Issuing CA.*

### Types of events recorded

*As stipulated in the CPS published by the Issuing CA.*

### Frequency of processing log

*As stipulated in the CPS published by the Issuing CA.*

### Retention period for audit log

*As stipulated in the CPS published by the Issuing CA.*

### Protection of audit log

*As stipulated in the CPS published by the Issuing CA.*

### Audit log backup procedures

*As stipulated in the CPS published by the Issuing CA.*

### Audit collection system (internal vs. external)

*As stipulated in the CPS published by the Issuing CA.*

### Notification to event-causing subject

*As stipulated in the CPS published by the Issuing CA.*

### Vulnerability assessments

*As stipulated in the CPS published by the Issuing CA.*

## Records Archival

*As stipulated in the CPS published by the Issuing CA.*

### Types of records archived

*As stipulated in the CPS published by the Issuing CA.*

### Retention period for archive

*As stipulated in the CPS published by the Issuing CA.*

### Protection of archive

*As stipulated in the CPS published by the Issuing CA.*

### Archive backup procedures

*As stipulated in the CPS published by the Issuing CA.*

### Requirements for time-stamping of records

*As stipulated in the CPS published by the Issuing CA.*

### Archive collection system (internal or external)

*As stipulated in the CPS published by the Issuing CA.*

### Procedures to obtain and verify archive information

*As stipulated in the CPS published by the Issuing CA.*

## Key Changeover

*As stipulated in the CPS published by the Issuing CA.*

## Compromise and Disaster Recovery

*As stipulated in the CPS published by the Issuing CA.*

### Incident and compromise handling procedures

*As stipulated in the CPS published by the Issuing CA.*

### Computing resources, software, and/or data are corrupted

*As stipulated in the CPS published by the Issuing CA.*

### Entity private key compromise procedures

*As stipulated in the CPS published by the Issuing CA.*

### Business continuity capabilities after a disaster

*As stipulated in the CPS published by the Issuing CA.*

## CA or RA Termination

*As stipulated in the CPS published by the Issuing CA.*

# Technical Security Controls

*Most of the stipulations of this section will refer to the CPS
published by the Issuing CA. In the following sections only particular
policies for SSL Certificates are stipulated, when appropriate.*

## Key Pair Generation and Installation

Under the **OGTM**, Key Pairs are generated under the necessary security
levels and always occurring in secure physical facilities and under the
adequate personnel control.

### Key pair generation

Key Pairs for SSL Certificates can be generated by software components,
except the “OISTE Qualified Personal/Corporate Certificates”, which must
be generated in Secure Signature Hardware Devices (FIPS 140-1 Level 2
and equivalents, or higher).

Subscribers who generate their own keys shall use a FIPS‐approved method
and either a validated hardware or validated software cryptographic
module, depending on the level of assurance desired.

### Private key delivery to subscriber

*As stipulated in the CPS published by the Issuing CA.*

### Public key delivery to certificate issuer

*As stipulated in the CPS published by the Issuing CA.*

### CA public key delivery to relying parties

*As stipulated in the CPS published by the Issuing CA.*

### Key sizes

The **CIDPKI** enforces the use of minimum length 2048-bit RSA and ECC
NIST P-256, P-384 for key pairs at all levels of the hierarchy.

Hashing algorithms supported is SHA-2, with different supported variants
depending on the hierarchy to which the end-entity certificate belongs,
as described in 1.3.1. In particular, no issuance of new SHA-1 SSL or CA
certificates after 31-December-2015.

### Public key parameters generation and quality checking

The algorithm used in the **OGTM** for key generation is RSA or ECC.

### Key usage purposes (as per X.509 v3 key usage field)

SSL Certificates assert key usages based on the intended application of
the Key Pair. In particular, Certificates to be used for digital
signatures (including authentication) set the digitalSignature and
keyEncipherment bits.

## Private Key Protection and Cryptographic Module Engineering Controls

The Issuing CA must establish controls to ensure that the risks derived
from a private key compromise are managed and kept under reasonable
levels.

### Cryptographic module standards and controls

Requirements for End-User cryptographic devices (if any) can vary in
terms of the expected assurance level, as indicated in section 6.1.1.

### Private key (n out of m) multi-person control

*As stipulated in the CPS published by the Issuing CA.*

### Private key escrow

*As stipulated in section 4.12 of this CP and in the CPS published by
the Issuing CA.*

### Private key backup

*Backup for SSL Certificates is considered equivalent of escrow and not
permitted, as stipulated in section 4.12 of this CP and in the CPS
published by the Issuing CA.*

### Private key archival

*The CA shall not provide key archival services.*

### Private key transfer into or from a cryptographic module

No stipulation

### Private key storage on cryptographic module

No stipulation additional to the requirements expressed in section 6.1.

### Method of activating private key

*As stipulated in the CPS published by the Issuing CA.*

### Method of deactivating private key

*As stipulated in the CPS published by the Issuing CA.*

### Method of destroying private key

*As stipulated in the CPS published by the Issuing CA.*

### Cryptographic Module Rating

No stipulation additional to section 6.2.1.

## Other Aspects of Key Pair Management

This section includes additional stipulations regarding key pair
management.

### Public key archival

*As stipulated in the CPS published by the Issuing CA.*

### Certificate operational periods and key pair usage periods

For SSL Certificates, the Certificate operational period is equivalent
to the key pair usage period and limited to 397 days.

## Activation Data

*As stipulated in the CPS published by the Issuing CA.*

### Activation data generation and installation

*As stipulated in the CPS published by the Issuing CA.*

### Activation data protection

*As stipulated in the CPS published by the Issuing CA.*

### Other aspects of activation data

No stipulation.

## Computer Security Controls

*As stipulated in the CPS published by the Issuing CA.*

### Specific computer security technical requirements

*As stipulated in the CPS published by the Issuing CA.*

### Computer security rating

*As stipulated in the CPS published by the Issuing CA.*

## Life Cycle Security Controls

*As stipulated in the CPS published by the Issuing CA.*

### System development controls

*As stipulated in the CPS published by the Issuing CA.*

### Security management controls

*As stipulated in the CPS published by the Issuing CA.*

### Life cycle security controls

*As stipulated in the CPS published by the Issuing CA.*

## Network Security Controls

*As stipulated in the CPS published by the Issuing CA.*

## Time-stamping

*As stipulated in the CPS published by the Issuing CA.*

# Certificate and CRL Profiles

All certificates issued under the **OGTM** are compliant to:

-   ITU-T Recommendation X.509 (1997): Information Technology - Open
    Systems Interconnection - The Directory: Authentication Framework,
    June 1997

-   RFC 5280: Internet X.509 Public Key Infrastructure Certificate and
    CRL Profile, April 2002 (“RFC 5280”).

## Certificate Profile

This section refers to the certificate profiles of SSL Certificates
issued under the OISTE Trust Model.

### Version number(s)

All certificates in the **OGTM** conform to X.509 Version 3.

### Certificate extensions

The different extension profiles for SSL Certificates are listed below.
This information is included as basic reference. Issuing CAs must
conform to the allowed certificate profiles mandated by the CAB/F
Baseline Requirements.

#### OISTE Standard DV SSL Certificate

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 56%" />
<col style="width: 7%" />
</colgroup>
<tbody>
<tr>
<td><strong>Authority Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">&lt;KeyID&gt;</td>
</tr>
<tr>
<td><strong>Subject Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical</td>
</tr>
<tr>
<td><strong>Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">The Subject Key Identifier of
the Subject of this certificate.</td>
</tr>
<tr>
<td><strong>CRL Distribution Point</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Full name</strong></td>
<td colspan="2" style="text-align: left;"><p>[1]CRL Distribution
Point</p>
<p>Distribution Point Name:</p>
<p>Full Name:</p>
<p>URL=&lt;URL-TO-CRL&gt;</p></td>
</tr>
<tr>
<td><strong>Policy Qualifier</strong></td>
<td colspan="2" style="text-align: left;">See section Policy
Qualifiers</td>
</tr>
<tr>
<td><strong>Authority Information Access</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Extensions</strong></td>
<td colspan="2" style="text-align: left;"><p>[1]Authority Info
Access</p>
<p>Access Method=Certification Authority Issuer (1.3.6.1.5.5.7.48.2)</p>
<p>Alternative Name:</p>
<p>URL=&lt;URL-TO-ISSUER-CERT&gt;</p></td>
</tr>
<tr>
<td><strong>Key Usage</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
critical.<br />
Allowed values: Digital Signature, Key Encipherment (a0)</td>
</tr>
<tr>
<td><strong>Extended Key Usage</strong></td>
<td colspan="2" style="text-align: left;">Client Authentication, Server
Authentication</td>
</tr>
<tr>
<td><strong>SubjectAltName</strong></td>
<td style="text-align: left;">&lt;List of SAN&gt; (at least one)</td>
<td style="text-align: left;"></td>
</tr>
</tbody>
</table>

#### OISTE Advanced OV SSL Certificate

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 56%" />
<col style="width: 7%" />
</colgroup>
<tbody>
<tr>
<td><strong>Authority Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">&lt;KeyID&gt;</td>
</tr>
<tr>
<td><strong>Subject Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical</td>
</tr>
<tr>
<td><strong>Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">The Subject Key Identifier of
the Subject of this certificate.</td>
</tr>
<tr>
<td><strong>CRL Distribution Point</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Full name</strong></td>
<td colspan="2" style="text-align: left;"><p>[1]CRL Distribution
Point</p>
<p>Distribution Point Name:</p>
<p>Full Name:</p>
<p>URL=&lt;URL-TO-CRL&gt;</p></td>
</tr>
<tr>
<td><strong>Policy Qualifier</strong></td>
<td colspan="2" style="text-align: left;">See Section Policy
Qualifiers</td>
</tr>
<tr>
<td><strong>Authority Information Access</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Extensions</strong></td>
<td colspan="2" style="text-align: left;"><p>[1]Authority Info
Access</p>
<p>Access Method=Certification Authority Issuer (1.3.6.1.5.5.7.48.2)</p>
<p>Alternative Name:</p>
<p>URL=&lt;URL-TO-ISSUER-CERT&gt;</p></td>
</tr>
<tr>
<td><strong>Key Usages</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
critical.<br />
Allowed Values: Data Encipherment, Digital Signature, Key
Encipherment</td>
</tr>
<tr>
<td><strong>Extended Key Usage</strong></td>
<td colspan="2" style="text-align: left;">Client Authentication, Server
Authentication</td>
</tr>
<tr>
<td><strong>SubjectAltName</strong></td>
<td style="text-align: left;">&lt;List of SAN&gt; (at least one)</td>
<td style="text-align: left;"></td>
</tr>
</tbody>
</table>

#### OISTE Advanced EV SSL Certificate

<table>
<colgroup>
<col style="width: 35%" />
<col style="width: 56%" />
<col style="width: 7%" />
</colgroup>
<tbody>
<tr>
<td><strong>Authority Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">&lt;KeyID&gt;</td>
</tr>
<tr>
<td><strong>Subject Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical</td>
</tr>
<tr>
<td><strong>Key Identifier</strong></td>
<td colspan="2" style="text-align: left;">The Subject Key Identifier of
the Subject of this certificate.</td>
</tr>
<tr>
<td><strong>CRL Distribution Point</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Full name</strong></td>
<td colspan="2" style="text-align: left;"><p>[1]CRL Distribution
Point</p>
<p>Distribution Point Name:</p>
<p>Full Name:</p>
<p>URL=&lt;URL-TO-CRL&gt;</p></td>
</tr>
<tr>
<td><strong>Policy Qualifier</strong></td>
<td colspan="2" style="text-align: left;">See Section Policy
Qualifiers</td>
</tr>
<tr>
<td><strong>Authority Information Access</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
non-critical.</td>
</tr>
<tr>
<td><strong>Extensions</strong></td>
<td colspan="2" style="text-align: left;"><p>[1]Authority Info
Access</p>
<p>Access Method=Certification Authority Issuer (1.3.6.1.5.5.7.48.2)</p>
<p>Alternative Name:</p>
<p>URL=&lt;URL-TO-ISSUER-CERT&gt;</p></td>
</tr>
<tr>
<td><strong>Key Usages</strong></td>
<td colspan="2" style="text-align: left;">Extension marked
critical.<br />
Allowed Values: Data Encipherment, Digital Signature, Key
Encipherment</td>
</tr>
<tr>
<td><strong>Extended Key Usage</strong></td>
<td colspan="2" style="text-align: left;">Client Authentication, Server
Authentication</td>
</tr>
<tr>
<td><strong>SubjectAltName</strong></td>
<td style="text-align: left;">&lt;List of SAN&gt; (at least one)</td>
<td style="text-align: left;"></td>
</tr>
</tbody>
</table>

### Algorithm object identifiers

The allowed Algorithm object identifiers are:

-   **sha256withRSAEncryption**:  
    OBJECT IDENTIFIER ::= {iso(1) member-body(2) us(840) rsadsi(113549)
    pkcs(1) pkcs-1(1) 11}

-   **ecdsa‐with‐SHA256**  
    OBJECT IDENTIFIER ::= {iso(1) member-body(2) us(840) rsadsi(10045)
    pkcs(4) pkcs-1(3) 2}

-   **ecdsa‐with‐SHA256**  
    OBJECT IDENTIFIER ::= {iso(1) member-body(2) us(840) rsadsi(10045)
    pkcs(4) pkcs-1(3) 3}

### Name forms

Certificates issued under the **OGTM** contain the “Distinguished Name”,
in X.500 format, for the issuer and the subscriber, set in the fields
“Issuer Name” and “Subject Name” respectively.

### Name constraints

No stipulation for subscriber certificates.

### Certificate policy object identifier

An object identifier (OID) is a unique number that identifies an object
or policy. The OIDs are administered by the **OGTM** and listed in the
Annex B of the CPS published by the OISTE Foundation, “OID Inventory”.

In particular for this CP, the following OID can be used:

**&lt;Public Arch&gt; = 2.16.756.5.14**

**&lt;PUBLIC-ARCH&gt;.4 – OISTE Certificate Policy Identifiers
(legacy)**

> 4.3.2.1.4 – OISTE Advanced SSL Certificate

**&lt;PUBLIC-ARCH&gt;.7 – OISTE Certificate Policy Identifiers
(current)**

> 7.4.6 – OISTE Standard SSL Certificate
>
> 7.4.7 – OISTE Advanced OV SSL Certificate
>
> 7.4.8 – OISTE Advanced EV SSL Certificate

**CAB/Forum Policy qualifiers for SSL Certificates (can be added to or
can substitute the OISTE OIDs when used in Publicly-Trusted
certificates)**

> 2.23.140.1.2.1 – OISTE Standard SSL Certificate
>
> 2.23.140.1.2.2 – OISTE OV SSL Certificate
>
> 2.23.140.1.1 – OISTE EV SSL Certificate

### Usage of Policy Constraints extension

No stipulation for subscriber certificates. The CA can disclose
additional stipulations in its CPS for CA certificates.

### Policy qualifiers syntax and semantics

No stipulation for subscriber certificates. The CA can disclose
additional stipulations in its CPS for CA certificates.

### Processing semantics for the critical Certificate Policies extension

The “Certificate Policy” extension identifies the Policy that the
**OGTM** assigned explicitly to a certificate profile. Software
Applications requiring a specific certificate profile to process a
digital signature must check this extension in order to verify the
suitability of the certificate for the intended purpose.

## CRL Profile

In general, CRLs generated under the **OGTM** Trust Model must be
compliant with RFC 5280 (Internet X.509 Public Key Infrastructure
Certificate and CRL Profile, April 2002).

### Version number(s)

CRLs conforming to X.509 Version 2 are supported in the **OGTM**.

### CRL Profile and CRL entry extensions

CRL must include the following minimum extensions, as defined by the
above standard:

-   CRL Number

-   Authority Key Identifier

-   Revocation date

-   Reason code

## OCSP Profile

Issuing CAs can optionally provide OCSP services for particular types of
SSL Certificates.

### Version number(s)

**OGTM** provides OCSP responses in accordance with industry standards.

### OCSP extensions

No stipulation.

# Compliance Audit and Other Assessment

This section is included in this CP document only for standardization
purposes. The reader must refer to the CPS published by the Issuing CA
for all the relevant stipulations.

## Frequency or circumstances of assessment

*As stipulated in the CPS published by the Issuing CA.*

## Identity/qualifications of assessor

*As stipulated in the CPS published by the Issuing CA.*

## Assessor's relationship to assessed entity

*As stipulated in the CPS published by the Issuing CA.*

## Topics covered by assessment

*As stipulated in the CPS published by the Issuing CA.*

## Actions taken as a result of deficiency

*As stipulated in the CPS published by the Issuing CA.*

## Communication of results

*As stipulated in the CPS published by the Issuing CA.*

# Other Business and Legal Matters

This section is included in this CP document only for standardization
purposes. The reader must refer to the CPS published by the Issuing CA
for all the relevant stipulations.

## Fees

*As stipulated in the CPS published by the Issuing CA.*

### Certificate issuance or renewal fees

*As stipulated in the CPS published by the Issuing CA.*

### Certificate access fees

*As stipulated in the CPS published by the Issuing CA.*

### Revocation or status information access fees

*As stipulated in the CPS published by the Issuing CA.*

### Fees for other services

*As stipulated in the CPS published by the Issuing CA.*

### Refund policy

*As stipulated in the CPS published by the Issuing CA.*

## Financial Responsibility

*As stipulated in the CPS published by the Issuing CA.*

### Insurance coverage

*As stipulated in the CPS published by the Issuing CA.*

### Other assets

*As stipulated in the CPS published by the Issuing CA.*

### Insurance or warranty coverage for end-entities

*As stipulated in the CPS published by the Issuing CA.*

## Confidentiality of Business Information

*As stipulated in the CPS published by the Issuing CA.*

### Scope of confidential information

*As stipulated in the CPS published by the Issuing CA.*

### Information not within the scope of confidential information

*As stipulated in the CPS published by the Issuing CA.*

### Responsibility to protect confidential information

*As stipulated in the CPS published by the Issuing CA.*

## Privacy of Personal Information

*As stipulated in the CPS published by the Issuing CA.*

### Privacy plan

*As stipulated in the CPS published by the subordinate CA.*

### Information treated as private

*As stipulated in the CPS published by the Issuing CA.*

### Information not deemed private

*As stipulated in the CPS published by the Issuing CA.*

### Responsibility to protect private information

*As stipulated in the CPS published by the Issuing CA.*

### Notice and consent to use private information

*As stipulated in the CPS published by the Issuing CA.*

### Disclosure pursuant to judicial or administrative process

*As stipulated in the CPS published by the Issuing CA.*

### Other information disclosure circumstances

*As stipulated in the CPS published by the Issuing CA.*

## Intellectual Property Rights

*As stipulated in the CPS published by the Issuing CA.*

## Representations and Warranties

*As stipulated in the CPS published by the Issuing CA.*

### CA representations and warranties

*As stipulated in the CPS published by the Issuing CA.*

### RA representations and warranties

*As stipulated in the CPS published by the Issuing CA.*

### Subscriber representations and warranties

*As stipulated in the CPS published by the Issuing CA.*

### Relying party representations and warranties

*As stipulated in the CPS published by the Issuing CA.*

### Representations and warranties of other participants

*As stipulated in the CPS published by the Issuing CA.*

## Disclaimers of Warranties

*As stipulated in the CPS published by the Issuing CA.*

## Limitations of Liability

*As stipulated in the CPS published by the Issuing CA.*

## Indemnities

*As stipulated in the CPS published by the Issuing CA.*

## Term and Termination

*As stipulated in the CPS published by the Issuing CA.*

### Term

*As stipulated in the CPS published by the Issuing CA.*

### Termination

*As stipulated in the CPS published by the Issuing CA.*

### Effect of termination and survival

*As stipulated in the CPS published by the Issuing CA.*

## Individual notices and communications with participants

*As stipulated in the CPS published by the Issuing CA.*

## Amendments

*As stipulated in the CPS published by the Issuing CA.*

### Procedure for amendment

*As stipulated in the CPS published by the Issuing CA.*

### Notification mechanism and period

*As stipulated in the CPS published by the Issuing CA.*

### Circumstances under which OID must be changed

*As stipulated in the CPS published by the Issuing CA.*

## Dispute Resolution Procedures

*As stipulated in the CPS published by the Issuing CA.*

## Governing Law

*As stipulated in the CPS published by the Issuing CA.*

## Compliance with Applicable Law

*As stipulated in the CPS published by the Issuing CA.*

## Miscellaneous Provisions

*As stipulated in the CPS published by the Issuing CA.*

### Entire agreement

*As stipulated in the CPS published by the Issuing CA.*

### Assignment

*As stipulated in the CPS published by the Issuing CA.*

### Severability

*As stipulated in the CPS published by the Issuing CA.*

### Enforcement (attorneys' fees and waiver of rights)

*As stipulated in the CPS published by the Issuing CA.*

### Force Majeure

*As stipulated in the CPS published by the Issuing CA.*

## Other Provisions

*As stipulated in the CPS published by the Issuing CA.*

# Annex A: Glossary

AATL Adobe Approved Trust List

CA Certificate Authority or Certification Authority

CAA Certification Authority Authorization

CAB ”CA/Browser” as in “CAB Forum”

CMS Card Management System

CP Certificate Policy

CPS Certification Practice Statement

CRL Certificate Revocation List

CSR Certificate Signing Request

CT Certificate Transparency

DBA Doing Business As (also known as "Trading As")

DV Domain Validated

ETSI European Telecommunications Standards Institute

EU European Union

EV Extended Validation

FIPS (US Government) Federal Information Processing Standard FQDN Fully
Qualified Domain Name

FTP File Transfer Protocol

HISP Health Information Service Provider

HSM Hardware Security Module

HTTP Hypertext Transfer Protocol

IANA Internet Assigned Numbers Authority

ICANN Internet Corporation for Assigned Names and Numbers IdM Identity
Management System

IDN Internationalized Domain Name

ISSO Information System Security Officer (also CSO, Chief Security
Officer)

IETF Internet Engineering Task Force

IGTF International Grid Trust Federation

ITU International Telecommunication Union

IV Individual Validated

MICS Member‐Integrated Credential Service (IGTF) NIST National Institute
of Standards and Technology OCSP Online Certificate Status Protocol

OID Object Identifier

OV Organization Validated

PAA Policy Approval Authority

PIN Personal Identification Number (e.g. a secret access code)

PKI Public Key Infrastructure

PKIX IETF Working Group on Public Key Infrastructure

RA Registration Authority

RFC Request for Comments (at IETF.org)

SAN Subject Alternative Name

SHA Secure Hashing Algorithm

SSL Secure Sockets Layer

TLD Top‐Level Domain

TLS Transport Layer Security

TSA Time Stamping Authority

TST Time‐Stamp Token

TTL Time To Live

UTC Coordinated Universal Time

X.509 The ITU‐T standard for Certificates and their corresponding
authentication framework
