# Table 1 – Domain Validation Methods in the CPS (TLS Server Certificates)

Validation logs include information about the method used for each domain. The validation is always conformant to the description of that methid in the latest version of the Baseline Requirements.

| # | Validation Method (CPS Name)                    | BR Reference               | Technical Mechanism                                                                                                    | Wildcard Allowed                              | Key Constraints / Notes                                                                       |
| - | ----------------------------------------------- | -------------------------- | ---------------------------------------------------------------------------------------------------------------------- | --------------------------------------------- | --------------------------------------------------------------------------------------------- |
| 1 | Email to Domain Contact                         | BR 3.2.2.4.13 / 3.2.2.4.14 | Email sent to domain contact obtained via DNS/CAA (WHOIS previously allowed) containing random validation code         | Yes (if domain-level validation sufficient)   | WHOIS-based contacts discontinued July 15, 2025. Random value validity ≤ 30 days.             |
| 2 | Constructed Email to Domain Contact             | BR 3.2.2.4.4               | Email sent to predefined role accounts (admin@, administrator@, webmaster@, hostmaster@, postmaster@) with random code | Yes                                           | Random value unique per request; validity ≤ 30 days; confirmation logs retained.              |
| 3 | Agreed-Upon Change to Website v2                | BR 3.2.2.4.18              | HTTP/HTTPS retrieval of CA-provided file at `/.well-known/pki-validation/<filename>` containing random value           | No (explicitly disallowed for Wildcards)      | HTTP GET must return 2xx; random value must not appear in request itself; ≤ 30 days validity. |
| 4 | DNS Change                                      | BR 3.2.2.4.7               | Placement of CA-provided random value in DNS (TXT, CNAME, or CAA record)                                               | Yes                                           | DNS-based proof of control; ≤ 30 days validity.                                               |
| 5 | Agreed-Upon Change to Website – ACME            | BR 3.2.2.4.19              | ACME HTTP-01 challenge (per Section 8.3 of RFC 8555)                                                                   | No (HTTP-01 not valid for Wildcards under BR) | Automated validation via ACME challenge; ≤ 30 days validity.                                  |
| 6 | Multi-Perspective Issuance Corroboration (MPIC) | BR 3.2.2.5                 | Corroboration of domain validation from multiple geographically and topologically distinct network perspectives        | N/A (corroboration mechanism)                 | Mandatory when required by BR effective dates; quorum rules applied; logs retained.           |

---

# Table 2 – CAB Forum Baseline Requirements: Introduction or Modification History

This table links the validation method used for each validation at time of issuance with the relevant BR version.

Reference standard: CA/Browser Forum Baseline Requirements (Server Certificate BRs).

> Note: Versions refer to major change points where the method was introduced, materially modified, or restricted.

| Validation Method                               | BR Section              | Introduced                    | Significant Modifications                                                                                        | Notes on Current Status                                                                  |
| ----------------------------------------------- | ----------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Email to Domain Contact                         | 3.2.2.4.13 / 3.2.2.4.14 | Pre-1.0 (legacy method)       | WHOIS-based contacts deprecated progressively; WHOIS reliance restricted/removed around BR 1.8.x era (2021–2023) | Still permitted if based on approved domain contact sources (not legacy WHOIS scraping). |
| Constructed Email to Domain Contact             | 3.2.2.4.4               | Early BR versions (≤1.0)      | Tightened entropy/randomness and reuse constraints over time                                                     | Still allowed.                                                                           |
| DNS Change                                      | 3.2.2.4.7               | Early BR versions             | TXT/CNAME clarified; CAA interaction clarified; DNSSEC considerations added                                      | Still widely used and permitted.                                                         |
| Agreed-Upon Change to Website v2                | 3.2.2.4.18              | Introduced in BR 1.7.3 (2021) | Replaced earlier HTTP validation variants; explicit restrictions for Wildcards                                   | Current standard HTTP file-based validation method.                                      |
| ACME HTTP-01                                    | 3.2.2.4.19              | Introduced in BR 1.6.x era    | Clarified alignment with ACME; HTTP-01 restricted from wildcard validation                                       | Still valid for FQDN (non-wildcard).                                                     |
| Multi-Perspective Issuance Corroboration (MPIC) | 3.2.2.5                 | Introduced in BR 2.0.0 (2023) | Gradual increase of required remote perspectives; quorum table defined                                           | Mandatory for remote domain validation methods as of staged effective dates (2023–2025). |

---
