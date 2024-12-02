---
title: OISTE/WISeKey Global Trust Model CP/CPS

subtitle: Version 4.0
author:
  - OISTE Policy Approval Authority

date: X-December-2024  





copyright: |
  Copyright 2024 OISTE Foundation

  This work is licensed under the Creative Commons Attribution 4.0 International license.
---

# 1.  INTRODUCTION
## 1.1  Overview

This document represents a combined Certificate Policy (CP) and Certification Practice Statement (CPS) describes the practices followed with regard to the management of the lifecycle the Certification Authorities adhered to the OISTE Global Trust Model.

The main two legal entities involved in the control and operation of the Trust Model are:
- OISTE Foundation. The International Organization for Secure Electronic Transactions (“IOSET” or “OISTE”), a Swiss non-profit foundation established in 1998, and recognized with an “Special Consultative Status” by the United Nations. The OISTE Foundation maintains a Policy Approval Authority (OFPAA or PAA) that drafts, approves and revises the policies to which WISeKey is bound to comply with under its operator contract. The PAA is composed of members of the community to which OISTE provides its Certification Authority Services, resulting in a virtuous cycle for trust management.
- WISeKey. WISeKey is referenced in this document as the short name for the entities “WISeKey International Holding Ltd.”, “WISeKey SA” or other members of the WISeKey Holding that are mandated by OISTE to host and operate the Root Certification Authorities and the technical infrastructures required to maintain the PKI at the appropriate operational level. WISeKey also operates as a “Subordinate Certification Authority” under the OISTE Roots, according to practices disclosed in this document.

The OISTE Global Trust Model (OGTM from now on) has been designed and are operated in accordance with the broad strategic direction of international PKI (Public Key Infrastructure) standards as well as their application to concrete identity frameworks in different domains (e.g. ID cards, passports, health cards, Internet of Things) and is intended to serve as a common Trust Model for Certification Authorities worldwide that comply with OISTE requirements.

The technologies, infrastructures, practices, and procedures implemented by the OGTM have been designed with explicit standards of security in mind based on the requirements approved by OISTE.

The OISTE Foundation, under Swiss law, cannot belong to any individual or company. It is subject to annual supervision by the Swiss Federal Government and audited annually by independent auditors. Such supervision and audit require the foundation to pursue the objectives that have been set out for it, which includes the promotion of security in electronic communications worldwide.

This document is developed per the recommendations found in the document RFC3647, developed by the Internet Engineering Task Force (IETF), which has been adopted as a worldwide-recognized standard framework to document the Certifications Practice Statement and related Certificate Policies disclosed by a Certification Services Provider.

The purpose of this document is to disclose the Practices and Policies adopted in the OGTM for the issuance of digital certificates. It is organized in the following sections:
1. Introductions – This section. Introduces the OGTM and this document.
2. Publication and Repositories Responsibilities – Describes the publication policies for the
certificates affected by this document, and the publication of this document itself.
1. Identification and Authentication – Discloses the rules for subscriber naming and required
authentication policies.
1. Certificate Life-Cycle Operational Requirements – This section describes the different phases in
the Life-Cycle of certificates and their requirements.
1. Management, Operational and Physical Controls – Describes the controls enforced in the OGTM to provide adequate trust levels in the certificates issued under the Trust Model.
2. Technical Security Controls – Discloses the security controls adopted in the OGTM.
3. Certificate and CRL Profiles – Describes the technical details of the different certificate types
issued under the OGTM.
1. Compliance Audit and other Assessment – Discloses the audit policies followed in the OGTM to
ensure that the participant fulfils the security and quality requirements.
1. Other Business and Legal Matters – This section exposes the commercial, legal and contractual
aspects involved in the usage of certificates issued in the OGTM.

**APPLICABILITY NOTICE:** If any inconsistency exists between this document and the normative provisions of an applicable industry guideline or standard (“Applicable Requirements”), then the Applicable Requirements take precedence over this CP/CPS. 

## 1.2  Document name and identification

| Name | OISTE/WISeKey Global Trust Model Certificate Policy/Certification Practices Statement (CP/CPS) |
| --- | --- |
| Version | 4.0 |
| OID | 2.16.756.5.14.7.1 |
| Issuance date | 1/1/2025 |
| Location | This document is published in https://oiste.org/repository and https://wisekey.com/repository |

## 1.3  PKI participants

### 1.3.1  Certification authorities

OISTE and WISeKey own and operate a number of Root and Issuing Certification Authorities (CAs) hierarchies that deliver certification Services under this CP/CPS.

These hierarchies are detailed in [Appendix B](#Appendix-B:-CA-Hierarchies) of this document.

OISTE and WISeKey also own and operate a number of Time Stamping Authorities (TSA), which are regulated by their corresponding Time Stamping Policy (TSP) document.

### 1.3.2  Registration authorities
The Registration Authorities are the physical or legal persons responsible for the identification of the entities requesting a certificate (referred as “applicants” when the request is in process and “subscribers” for those in possession of a certificate). The @#@CIDPKI delegates to Registration Authorities the responsibility of verifying the information provided by the applicant within a certificate request, ensuring that the requestand the process used to deliver the certificate to the subscriber meets the requirements of this CPS and the appropriate CP.

The Registration Authorities in the CIDPKI are directly supervised by the CA and follow an accreditation process imposed by the CA in order to ensure that all security and operational procedures related to the certificates life-cycle are strictly enforced. Within the CIDPKI environment there exist locations named “CIDPKI Registration Point” that are the physical or virtual locations where a Registration Authority operates. These Registration Points are operated by “Registration Authority Officers”, who are authorized persons responsible for verifying the identity and veracity of a certificate request for an end entity and the delivery of the certificate once issued by the Certification Authority.

Therefore, the responsibilities of Registration Authorities operating under the CIDPKI are as follows:
- Check the identity and circumstances needed to verify that a certificate request is valid according to the type of certificate requested.
- Inform the applicant, before the issuance of the certificate, about the terms and conditions related to the certificate and its usage.
- Verify that the information contained in a certificate is exact and complete according to the requirements of the corresponding CP.
- Ensure that the subscriber is in possession of the digital signature creation data (private keys) associated to the certificate to be issued.

Currently is not supported the existence of Registration Authorities which are entitled to issue SSL or Code Signing certificates without the participation of WISeKey for the domain validation. WISeKey supports the concept of “Managed PKI” services for pre-authorized internet domains.

### 1.3.3  Subscribers

In the CIDPKI two different end-user roles are defined. Depending on the status of the certificate request, these roles are named “Applicant” and “Subscriber”.
- An applicant is a physical person that requests a certificate for his own behalf or on behalf of a third party. The applicant needs to accredit his identity and ability to request a certificate. In the case of an applicant acting on behalf of a third party or legal person, he will be requested to accredit the empowerment for such representation, as required by law.
- A subscriber is the physical or legal person whose identity is linked to the electronic signature creation data, or private key, and included in a digital certificate. In general, a subscriber is considered the “owner” of a certificate. The subscriber of a certificate is responsible for the custody of his private key and not communicating this data in any way to any other person.

This document details the particular community of subscribers to whom each type of certificate is aimed and what identification and other security requirements should be fulfilled.

### 1.3.4 Relying parties

All natura and legal persons and other entities that trust the certificates issued by certification authorities operating under the CIDPKI Trust Model are considered to be “relying parties”. These relying parties do not necessarily need to be a subscriber of an CIDPKI certificate, but are requested to accept the “CertifyID Relying Party agreement“, available at http://oiste.org/repository.

In the OGTM, a particular type of certificate could limit the right to be a relying party for that particular type of certificate, if this is the case, a specific Relying Party agreement would be published.

### 1.3.5  Other participants

No stipulation.

## 1.4  Certificate usage

In the CIDPKI, the limitations for certificate usage are established for each particular certificate type. This information is summarized in the following subsections.
The type of certificate is determined by the combination of "Key Usage", "Extended Key Usage", and Policy Identifiers.

### 1.4.1  Appropriate certificate uses

| Certificate type | Description | Permitted uses |
| --- | --- | --- |
| Issuing and Intermediate CA Certificate | Infrastructure certificate for all subordinate Certification Authorities operating in the trust model | Certificate Signing, CRL Signing |
| OCSP Certificate | Infrastructure certificate for Online Certificate Status Responders providing information on the subordinated CAs issued by the OISTE Roots | OCSP Response Signature |
| Standard Personal Certificate | Low Assurance Personal certificates used by Natural persons to authenticate and encrypt documents and transactions. Only the eMail address is verified and included in the certificate | Digital Signature, Encryption, Client Authentication and email Protection |
| Advanced Personal Certificate | High Assurance Personal certificates with software keys, used by Natural person to authenticate and encrypt documents and transactions. Personal and Organizations identity attributes are validated and included in the certificate. Remote verification is allowed under certain circumstances | Digital Signature, Encryption, Client Authentication, Non- Repudiation and email Protection |
| Qualified Personal Certificate | High Assurance Personal certificates with FIPS-protected keys, used by Natural persons authenticate and encrypt documents and transactions. Personal and Organizations identity attributes are validated and included in the certificate. All identification attributes in the certificate are verified “Face-to-Face” or similar assurance | Digital Signature, Encryption, Client Authentication, Non-Repudiation and email Protection |
| DV SSL Certificate | Medium assurance SSL/TLS certificate. All identification attributes in the certificate are verified. The control on the Internet Domain is validated. Compliant with CA/Browser Forum Baseline Requirements | Digital Signature, Encryption, Server Authentication |
| OV SSL Certificate | High assurance SSL/TLS certificate. All identification attributes in the certificate are verified. The Identity of the organization is validated. Compliant with CA/Browser Forum Baseline Requirements | Digital Signature, Encryption, Server Authentication |
| OISTE Advanced EV SSL Certificate | High assurance SSL/TLS certificate | All identification attributes in the certificate are verified. The Identity of the organization is validated. Compliant with CA/Browser Requirements for Extended Validation | Digital Signature, Encryption, Server Authentication |
| Device Certificate | High Assurance Device certificates used by devices to authenticate themselves and to protect transactions over IoT networks. Identity information as model number, serial number and manufacturer information are validated. Remote validation is allowed under certain circumstances | Digital Signature, Encryption, Client Authentication |

### 1.4.2 Prohibited certificate uses

In general, any usage that is not explicitly stated in section 1.4.1 of this document or the appropriate CP, is considered to be prohibited.

## 1.5  Policy administration
### 1.5.1  Organization administering the document

This document is administered by the OGTM Policy Approval Authority (referred from now as PAA).

The PAA has a series of distinct functions but does not operate as a separate legal Entity. It is managed and organized in accordance with a process that draws on expertise within the OISTE Foundation and WISeKey. The PAA has been established to develop, review and/or approve the practices, policies and procedures for the entire Trust Model, subject to guidelines established by the members and advisors of the OISTE Foundation and WISeKey.

### 1.5.2  Contact person

- **Name:** OISTE Foundation - OGTM Policy Approval Authority
- **email address:** cps@oiste.org, cps@wisekey.com
- **Address:** Avenue Louis-Casaï 58 - 1216 Cointrin - Switzerland

This same contact can also be used for revocation requests and compliance-related notifications.

### 1.5.3  Person determining CPS suitability for the policy

The competent entity which determines the compliance and suitability of all CPS and the different supported CPs on behalf of the entire Trust Model is the OGTM PAA.

### 1.5.4  CPS approval procedures

The OGTM PAA defines and executes the procedures related to the approval of the CPS and CP and its subsequent amendments. Amendments will produce a new version of the document that will be published in the OGTM Policy Repository (specified in section 2.1 of this document).

The approval of major changes of documents related to the PKI, and specially for the CP/CPS, require a meeting of the PAA and the issuance of an approval memo signed by at least two members of the PAA. Minor versions only require the participation of a single member of the PAA in order to approve the publication of a new version.

It’s required to issue new CP/CPS versions at least once a year. In the case of versioning conflict, the latest version that prevails is always the document published in the Policy Repository.

Once any document of the Trust Model is updated, the CAs must do a technical assessment to identify any possible impact and/or required configuration changes in the platforms.

## 1.6  Definitions and acronyms

Definitions and Acronyms are included in [Annex A](#-Appendix-A:-Glossary)

# 2. PUBLICATION AND REPOSITORY RESPONSIBILITIES
## 2.1  Repositories

The main repositories of the CIDPKI are:
- Policies repository for disclosure of CP/CPS and related information. This repository is a set of web pages and services available at the URLs https://oiste.org and https://wisekey.com/repository
- Certificate and Certificate Revocation information repositories. The CA certificates and Certificate Revocation Information sources are included, when relevant, as CDP and AIA extensions in the certificates issued under the OSITE Root CAs
- Public Certificate repositories. Publicly accessible certificate information repositories optionally maintained by the operators of the Certification Authorities operating under the OWGTM are disclosed appropriately to the relying parties of these certificates

## 2.2  Publication of certification information

The OGTM is responsible for publication of information regarding practices, certificates, and the current status of certificates. Where appropriate, such responsibilities may be delegated to the Subordinate CAs operating under the OISTE Trust Model.

The shared repositories containing public information in the OGTM are managed by WISeKey SA or the operator of the Issuing CAs, and are available 24 hours a day, seven days a week. In the case of interruption by cause of “force majeure”, the service will be re-established in the minimum possible time.

### 2.2.1 Statement on Compliance with CA/Browser Forum requirements
OISTE and WISeKey ensure the compliance with industry best practices and security controls. In particular, the trust model enforces regular review and compliance with the latest version of the “Baseline Requirements” and “Extended Validation Requirements” for the certificate profiles to which these regulations apply (these requirements are available respectively at https://cabforum.org/ )

In the case of discrepancy of any certification practices with the stipulations of the CAB/Forum requirements, it must be understood that those requirements must prevail to this CPS.

## 2.3  Time or frequency of publication

The CP/CPS documents will be published every time they are modified, with a minimum review period of one year.
A certificate issued by any CA under the OGTM will be published immediately after its issuance.

In the case of revocation of a certificate, the appropriate CA will include this revocation information in the
Certificate Revocation Lists (CRL) according to section 4.9.7 (CRL issuance frequency).

## 2.4  Access controls on repositories

The OGTM makes its Repository publicly available in a read-only manner.

# 3. IDENTIFICATION AND AUTHENTICATION
## 3.1  Naming
### 3.1.1  Types of names
### 3.1.2  Need for names to be meaningful
### 3.1.3  Anonymity or pseudonymity of subscribers
### 3.1.4  Rules for interpreting various name forms
### 3.1.5  Uniqueness of names
### 3.1.6  Recognition, authentication, and role of trademarks
## 3.2  Initial identity validation
### 3.2.1  Method to prove possession of private key
### 3.2.2  Authentication of organization identity
### 3.2.3  Authentication of individual identity
### 3.2.4  Non-verified subscriber information
### 3.2.5 Validation of authority
### 3.2.6  Criteria for interoperation
## 3.3  Identification and authentication for re-key requests
### 3.3.1  Identification and authentication for routine re-key
### 3.3.2  Identification and authentication for re-key after revocation
## 3.4 Identification and authentication for revocation request
# 4.  CERTIFICATE LIFE-CYCLE OPERATIONAL REQUIREMENTS
## 4.1  Certificate Application
### 4.1.1  Who can submit a certificate application
### 4.1.2  Enrollment process and responsibilities
## 4.2 Certificate application processing
### 4.2.1 Performing identification and authentication functions
### 4.2.2 Approval or rejection of certificate applications
### 4.2.3  Time to process certificate applications
## 4.3  Certificate issuance
### 4.3.1  CA actions during certificate issuance
### 4.3.2  Notification to subscriber by the CA of issuance of certificate
## 4.4  Certificate acceptance
### 4.4.1  Conduct constituting certificate acceptance
### 4.4.2  Publication of the certificate by the CA
### 4.4.3  Notification of certificate issuance by the CA to other entities
## 4.5 Key pair and certificate usage
### 4.5.1  Subscriber private key and certificate usage
### 4.5.2  Relying party public key and certificate usage
## 4.6  Certificate renewal
### 4.6.1  Circumstance for certificate renewal
### 4.6.2  Who may request renewal
### 4.6.3  Processing certificate renewal requests
### 4.6.4  Notification of new certificate issuance to subscriber
### 4.6.5  Conduct constituting acceptance of a renewal certificate
### 4.6.6  Publication of the renewal certificate by the CA
### 4.6.7  Notification of certificate issuance by the CA to other entities
## 4.7  Certificate re-key
### 4.7.1  Circumstance for certificate re-key
### 4.7.2  Who may request certification of a new public key
### 4.7.3  Processing certificate re-keying requests
### 4.7.4  Notification of new certificate issuance to subscriber
### 4.7.5  Conduct constituting acceptance of a re-keyed certificate
### 4.7.6  Publication of the re-keyed certificate by the CA
### 4.7.7  Notification of certificate issuance by the CA to other entities
## 4.8  Certificate modification
### 4.8.1  Circumstance for certificate modification
### 4.8.2  Who may request certificate modification
### 4.8.3  Processing certificate modification requests
### 4.8.4  Notification of new certificate issuance to subscriber
### 4.8.5  Conduct constituting acceptance of modified certificate
### 4.8.6  Publication of the modified certificate by the CA
### 4.8.7  Notification of certificate issuance by the CA to other entities
## 4.9  Certificate revocation and suspension
### 4.9.1  Circumstances for revocation
### 4.9.2  Who can request revocation
### 4.9.3  Procedure for revocation request
### 4.9.4  Revocation request grace period
### 4.9.5  Time within which CA must process the revocation request
### 4.9.6  Revocation checking requirement for relying parties
### 4.9.7 CRL issuance frequency (if applicable)
### 4.9.8 Maximum latency for CRLs (if applicable)
### 4.9.9  On-line revocation/status checking availability
### 4.9.10 On-line revocation checking requirements
### 4.9.11 Other forms of revocation advertisements available
### 4.9.12 Special requirements re key compromise
### 4.9.13 Circumstances for suspension
### 4.9.14 Who can request suspension
### 4.9.15 Procedure for suspension request
### 4.9.16 Limits on suspension period
## 4.10  Certificate status services
### 4.10.1 Operational characteristics
### 4.10.2 Service availability
### 4.10.3 Optional features
## 4.11  End of subscription
## 4.12  Key escrow and recovery
### 4.12.1 Key escrow and recovery policy and practices
### 4.12.2 Session key encapsulation and recovery policy and practices
# 5.  FACILITY, MANAGEMENT, AND OPERATIONAL CONTROLS (11)
## 5.1  Physical controls
### 5.1.1  Site location and construction
### 5.1.2  Physical access
### 5.1.3  Power and air conditioning
### 5.1.4  Water exposures
### 5.1.5  Fire prevention and protection
### 5.1.6  Media storage
### 5.1.7  Waste disposal
### 5.1.8  Off-site backup
## 5.2  Procedural controls
### 5.2.1  Trusted roles
### 5.2.2  Number of persons required per task
### 5.2.3  Identification and authentication for each role
### 5.2.4  Roles requiring separation of duties
## 5.3  Personnel controls
### 5.3.1  Qualifications, experience, and clearance requirements
### 5.3.2  Background check procedures
### 5.3.3  Training requirements
### 5.3.4  Retraining frequency and requirements
### 5.3.5  Job rotation frequency and sequence
### 5.3.6  Sanctions for unauthorized actions
### 5.3.7  Independent contractor requirements
### 5.3.8  Documentation supplied to personnel
## 5.4  Audit logging procedures
### 5.4.1  Types of events recorded
### 5.4.2  Frequency of processing log
### 5.4.3  Retention period for audit log
### 5.4.4  Protection of audit log
### 5.4.5  Audit log backup procedures
### 5.4.6  Audit collection system (internal vs. external)
### 5.4.7  Notification to event-causing subject
### 5.4.8  Vulnerability assessments
## 5.5  Records archival
### 5.5.1  Types of records archived
### 5.5.2  Retention period for archive
### 5.5.3  Protection of archive
### 5.5.4  Archive backup procedures
### 5.5.5  Requirements for time-stamping of records
### 5.5.6  Archive collection system (internal or external)
### 5.5.7  Procedures to obtain and verify archive information
## 5.6  Key changeover
## 5.7  Compromise and disaster recovery
### 5.7.1  Incident and compromise handling procedures
### 5.7.2  Computing resources, software, and/or data are corrupted
### 5.7.3  Entity private key compromise procedures
### 5.7.4  Business continuity capabilities after a disaster
## 5.8  CA or RA termination
# 6.  TECHNICAL SECURITY CONTROLS (11)
## 6.1  Key pair generation and installation
### 6.1.1  Key pair generation
### 6.1.2  Private key delivery to subscriber
### 6.1.3  Public key delivery to certificate issuer
### 6.1.4  CA public key delivery to relying parties
### 6.1.5  Key sizes
### 6.1.6  Public key parameters generation and quality checking
### 6.1.7  Key usage purposes (as per X.509 v3 key usage field)
## 6.2  Private Key Protection and Cryptographic Module Engineering Controls
### 6.2.1  Cryptographic module standards and controls
### 6.2.2  Private key (n out of m) multi-person control
### 6.2.3  Private key escrow
### 6.2.4  Private key backup
### 6.2.5  Private key archival
### 6.2.6  Private key transfer into or from a cryptographic module
### 6.2.7  Private key storage on cryptographic module
### 6.2.8  Method of activating private key
### 6.2.9  Method of deactivating private key
### 6.2.10 Method of destroying private key
### 6.2.11 Cryptographic Module Rating
## 6.3  Other aspects of key pair management
### 6.3.1  Public key archival
### 6.3.2  Certificate operational periods and key pair usage periods
## 6.4  Activation data
### 6.4.1  Activation data generation and installation
### 6.4.2  Activation data protection
### 6.4.3  Other aspects of activation data
## 6.5  Computer security controls
### 6.5.1  Specific computer security technical requirements
### 6.5.2  Computer security rating
## 6.6  Life cycle technical controls
### 6.6.1  System development controls
### 6.6.2  Security management controls
### 6.6.3  Life cycle security controls
## 6.7  Network security controls
## 6.8  Time-stamping
# 7.  CERTIFICATE, CRL, AND OCSP PROFILES
## 7.1  Certificate profile
### 7.1.1  Version number(s)
### 7.1.2  Certificate extensions
### 7.1.3  Algorithm object identifiers
### 7.1.4  Name forms
### 7.1.5  Name constraints
### 7.1.6  Certificate policy object identifier
### 7.1.7  Usage of Policy Constraints extension
### 7.1.8  Policy qualifiers syntax and semantics
### 7.1.9 Processing semantics for the critical Certificate Policies extension
## 7.2  CRL profile
### 7.2.1  Version number(s)
### 7.2.2  CRL and CRL entry extensions
## 7.3  OCSP profile
### 7.3.1  Version number(s)
### 7.3.2  OCSP extensions
# 8.  COMPLIANCE AUDIT AND OTHER ASSESSMENTS
## 8.1  Frequency or circumstances of assessment
## 8.2  Identity/qualifications of assessor
## 8.3  Assessor's relationship to assessed entity
## 8.4  Topics covered by assessment
## 8.5  Actions taken as a result of deficiency
## 8.6  Communication of results
# 9.  OTHER BUSINESS AND LEGAL MATTERS
## 9.1  Fees
### 9.1.1  Certificate issuance or renewal fees
### 9.1.2  Certificate access fees
### 9.1.3  Revocation or status information access fees
### 9.1.4  Fees for other services
### 9.1.5  Refund policy
## 9.2  Financial responsibility
### 9.2.1  Insurance coverage
### 9.2.2  Other assets
### 9.2.3  Insurance or warranty coverage for end-entities
## 9.3  Confidentiality of business information
### 9.3.1  Scope of confidential information
### 9.3.2  Information not within the scope of confidential information
### 9.3.3  Responsibility to protect confidential information
## 9.4  Privacy of personal information
### 9.4.1  Privacy plan
### 9.4.2  Information treated as private
### 9.4.3  Information not deemed private
### 9.4.4  Responsibility to protect private information
### 9.4.5  Notice and consent to use private information
### 9.4.6 Disclosure pursuant to judicial or administrative process
### 9.4.7  Other information disclosure circumstances
## 9.5  Intellectual property rights
## 9.6  Representations and warranties
### 9.6.1  CA representations and warranties
### 9.6.2  RA representations and warranties
### 9.6.3  Subscriber representations and warranties
### 9.6.4  Relying party representations and warranties
### 9.6.5  Representations and warranties of other participants
## 9.7  Disclaimers of warranties
## 9.8  Limitations of liability
## 9.9  Indemnities
## 9.10  Term and termination
### 9.10.1  Term
### 9.10.2  Termination
### 9.10.3  Effect of termination and survival
## 9.11  Individual notices and communications with participants
## 9.12  Amendments
### 9.12.1  Procedure for amendment
### 9.12.2  Notification mechanism and period
### 9.12.3  Circumstances under which OID must be changed
## 9.13  Dispute resolution provisions
## 9.14  Governing law
## 9.15  Compliance with applicable law
## 9.16  Miscellaneous provisions
### 9.16.1  Entire agreement
### 9.16.2  Assignment
### 9.16.3  Severability
### 9.16.4  Enforcement (attorneys' fees and waiver of rights)
### 9.16.5  Force Majeure
## 9.17  Other provisions
# Appendix A: Glossary
# Appendix B: CA Hierarchies
