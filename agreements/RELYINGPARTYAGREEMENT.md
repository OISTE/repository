# RELYING PARTY AGREEMENT

WISEKEY S.A. OPERATES THE OISTE WISEKEY ROOT PKI UNDER THE PRE-CONDITION THAT ALL RELIANCE ON THE DATA AND CERTIFICATION SERVICES PROVIDED BY WISEKEY BE SUBJECT TO THE RELYING PARTY CONSENTING TO THIS RELYING PARTY AGREEMENT. 

CONSENT TO THE TERMS AND CONDITIONS OF THIS RELYING PARTY AGREEMENT IS INDICATED BY ACCESSING THE OISTE WISEKEY ROOT CA CERTIFICATE OR ANY CERTIFICATE OR CERTIFICATE REVOCATION LISTS (CRLS) ISSUED BY THE OISTE WISEKEY ROOT CA, AS WELL AS OTHER DATA AND INFORMATION PROVIDED BY WISEKEY OR SUBORDINATE PKI ENTITIES (E.G. CERTIFICATE REVOCATION LISTS, OCSP CERTIFICATE STATUS DATA, CERTIFICATION PRACTICES AND POLICIES). 

 
## Definitions & Incorporation by Reference
The definitions contained in the OISTE/WISEKEY CP/CPS Glossary shall apply to this Agreement (available at https://www.oiste.org/repository/.

The OISTE/WISEKEY Certificate Policy and Certification Practice Statement and the Privacy Policy, certification services or other data relied upon are incorporated herein by reference. All such documents are freely available at the WISeKey Web Site (https://www.wisekey.com/repository/) 

## Warranties to Relying Party
1.	WISeKey hereby warrants to all Relying Parties who have complied with their obligations under this agreement that:
    - it complies with its Certification Practice Statement in the provision of its certification services;
    - the information contained in the certificates issued by it was verified in accordance with the Certification Practice Statement and that at the time of the verification, such information was deemed true and accurate as a result of the verification procedures undertaken;
    - the information contained in the certificate was accurately transcribed and meets all of the material requirements of the Certification Practice Statement.; and
    - the certificate revocation lists issued by it are accurate and are updated and published periodically in accordance with the OISTE/WISeKey CP/CPS.
2.	WISeKey assumes no other warranties or obligations in the purview of its activities as described in the OISTE/WISeKey CP/CPS and Subscriber Agreement. 

## Relying Party Obligations

1. Upon consenting to this agreement, the Relying Party undertakes to observe the following obligations:
    - verify the validity, suspension or revocation of the certificate using current revocation status information and taking into consideration the delays in the dissemination of certificate status information (available in the certificate as CDP and/or AIA OCSP Extensions).
    - take account of any limitations on the usage and financial reliance limits of the certificate indicated in the Certification Practice Statement; 
    - Securely obtain the OISTE WISeKey Root CA Certificate and any other certificates within the corresponding certificate chain (available at https://www.oiste.org/repository/ )
    - Only rely on digital signatures and certificates when such reliance is deemed reasonable. In considering the reasonableness of reliance the aspects to be considered shall include whether: 
        - the digital signature was created during the validity period of the certificate;
        - the digital signature can be verified successfully;
        - all of the public key hashes (thumbprints) on the certificates within the corresponding certificate chain are verified successfully;
        - the certificates  in the certificate chain have not expired;
        - the certificate and certificate chain are successfully validated; 
        - there are no additional circumstances that may affect the reliability of the digital signature, certificate, certificate chain or certificate revocation list. 

    Where the foregoing verifications are undertaken by software, WISeKey disclaims any and all responsibility for failures in the verification undertaken by such software.  
4.	Upon consenting to this agreement, the Relying Party acknowledges that the certification services provided by WISeKey are governed by the OISTE/WISeKey Certificate Policy and Certification Practice Statement.

## Unreasonable Reliance
In the cases in which reliance is not reasonable, the Relying Party relies at its own risk and therefore waives any and all warranties provided by WISeKey or other entity that forms part of the OISTE WISeKey Root PKI.

## Intellectual Property Rights
As determined in the OISTE/WISeKey CP/CPS, all Intellectual Property Rights including copyright in all certificates, certificate revocation lists, OCSP certificate status messages, certificate directories and, unless otherwise explicitly provided for, all practices, policies, operational and security documents concerning the OISTE WISeKey Root PKI (electronic or otherwise) as well as agreements, belong to and will remain the property of WISeKey.

Unless otherwise explicitly stated, the use of such protected material by the Relying Party shall be limited to the assessment on whether reliance is reasonable or not. This explicitly excludes the use, access to, download, copying, or reproduction by any third party and further excludes any publication, distribution, modification, creation of derivative works, compilation, aggregation, renting, leasing, transfer, assignment, sublicensing or other similar acts by the Relying Party or a third party, whether done manually, by electronic means or other direct or indirect method, such as software performing any such acts. 

## Liability Limits and Disclaimers
1.	Liability Limits to Subscribers: The disclaimers and liability clauses of the OISTE/WISeKey CP/CPS and Subscriber Agreement operate with regard to all claims arising in relation to certificates and certification services provided by WISeKey and any authorised third parties. The foregoing limitations shall apply to any liability whether based in contract, tort (including negligence) or any other theory of liability, including any direct, indirect, special, punitive, exemplary, consequential, reliance, or incidental damages.
2. Liability Limits to non-subscriber Relying Parties. The following table represents the liability limits in these cases:

    | Certificate Class | Liability Cap |
    | --- | --- |
    | Personal Certificates | 100 CHF (or the local currency equivalent thereof) per Relying Party per certificate.<br>1,000 CHF (or the local currency equivalent thereof) aggregate per certificate. |
    | DV | 100 CHF (or the local currency equivalent thereof) per Relying Party per certificate.<br>1,000 CHF (or the local currency equivalent thereof) aggregate per certificate. |
    | OV | 1,000 CHF (or the local currency equivalent thereof) per Relying Party per certificate.<br>10,000 CHF (or the local currency equivalent thereof) aggregate per certificate. |
    | EV | 10,000 CHF (or the local currency equivalent thereof) per Relying Party per certificate.<br>50,000 CHF (or the local currency equivalent thereof) aggregate per certificate.  |

## Severability

If any section, sentence, clause or phrase of this agreement should be held to be invalid or unconstitutional by a court of competent jurisdiction, such invalidity or unconstitutionality shall not affect the validity or constitutionality of any other section, sentence, clause or phrase of this agreement. 

## Applicable Law

This agreement shall be governed and interpreted in accordance with the laws of Switzerland and the parties consent to the exclusive jurisdiction of the Swiss courts.


